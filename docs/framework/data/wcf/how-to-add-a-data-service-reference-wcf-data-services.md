---
title: "How to: Add a Data Service Reference (WCF Data Services)"
ms.date: 08/24/2018
helpviewer_keywords:
  - "WCF Data Services, configuring"
ms.assetid: 62c6f318-3ee1-433a-b7a3-efa234c3034c
---
# How to: Add a data service reference (WCF Data Services)

You can use the **Add Service Reference** dialog in Visual Studio to add a reference to WCF Data Services. This enables you to more easily access a data service in a client application that you develop in Visual Studio. When you complete this procedure, data classes are generated based on metadata that is obtained from the data service. For more information, see [Generating the Data Service Client Library](../../../../docs/framework/data/wcf/generating-the-data-service-client-library-wcf-data-services.md).

## Add a data service reference

1. (Optional) If the data service is not part of the solution and is not already running, start the data service and note the URI of the data service.

2. In Visual Studio, in **Solution Explorer**, right-click the client project and then select **Add** > **Service Reference**.

3. If the data service is part of the current solution, click **Discover**.

     -or-

     In the **Address** text box, type the base URL of the data service, such as `http://localhost:1234/Northwind.svc`, and then click **Go**.

4. Select **OK**.

     A new code file that contains the data classes that can access and interact with data service resources is added to the project.

## See also

- [Quickstart](../../../../docs/framework/data/wcf/quickstart-wcf-data-services.md)