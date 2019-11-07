# Welcome to Windows Virtual Desktop Rapid Storage Deployment

This has been developed to allow you to rapidly deploy storage for any WVD deployment that can instantly scale between 200 - 5120 users per deployment*. 

It uses best practices documented here (https://docs.microsoft.com/azure/virtual-desktop/create-fslogix-profile-container) and deploys securely within your Azure environment.

**Based on the default FSLogix quota of 20GB per user profile*



# Profile Container Storage

Windows Virtual Desktop (WVD) Rapid Deployment uses **enterprise class** Microsoft Azure storage:  **Azure NetApp Files**.  Microsoft launched the Azure NetApp Files (ANF) service in May 2019 and it is now GA in over 10 regions globally. The benefits of using ANF for WVD, Shared Files and FSLogix are:

 1. **Scalability** - Easily scale from 200 - 5120 users on demand (**per volume**), In addition,  you can deploy multiple volumes* in order to support up to a **staggering 6,400,000 user profile containers** in a single Azure subscription.
 2. **Reliability** - The ANF service is enterprise class, ensuring that your storage is highly available
 3. **Performance** - Unrivaled performance for shared file storage in any cloud provider. Ensure your users have great usability and responsiveness to increase their productivity.
 4. **Simplicity** - The service requires no storage adminstration - simply chose a performance tier and size (GB/TB) and your storage will deploy in minutes.

*500TB per capacity pool, 25 capacity pools per ANF account, 10 ANF accounts per Azure Subscription ([https://docs.microsoft.com/en-us/azure/azure-netapp-files/azure-netapp-files-resource-limits](https://docs.microsoft.com/en-us/azure/azure-netapp-files/azure-netapp-files-resource-limits)

# Deployment Instructions
Simply follow this guide in order to deploy storage for your WVD environment in minutes.
