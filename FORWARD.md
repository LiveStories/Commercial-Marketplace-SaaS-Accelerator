```
cd ./deployment
.\Deploy.ps1 `
 -WebAppNamePrefix "fwd-case-mgmt" `
 -ResourceGroupForDeployment "fwdfedev0rg" `
 -PublisherAdminUsers "regis.anclades@forwardplatform.com,regis.anclades@livestories.com" `
 -Location "West US" `
 -TenantID "e34f2bd8-0f32-4d15-a9a1-4b96a16d51e3" `
 -AzureSubscriptionID "e32b6a1d-5183-4d1f-9d68-6f5a7381a724" `
 -LogoURLico "https://forwardplatform.com/wp-content/uploads/2022/10/cropped-forward_ico-32x32.png"
```

logo upload didn't work
```
cd ./deployment
.\Deploy.ps1 `
 -WebAppNamePrefix "fwd-case-mgmt" `
 -ResourceGroupForDeployment "fwdfedev0rg" `
 -PublisherAdminUsers "regis.anclades@forwardplatform.com,regis.anclades@livestories.com" `
 -Location "West US" `
 -TenantID "e34f2bd8-0f32-4d15-a9a1-4b96a16d51e3" `
 -AzureSubscriptionID "e32b6a1d-5183-4d1f-9d68-6f5a7381a724" `
 -LogoURLpng "https://forward.livestories.com/static/media/Forward-Blue.dbec8bc456fbd0f5c40d.png" `
 -LogoURLico "https://forwardplatform.com/wp-content/uploads/2022/10/cropped-forward_ico-32x32.png"
```

```
wget https://dotnet.microsoft.com/download/dotnet/scripts/v1/dotnet-install.sh; `
chmod +x dotnet-install.sh; `
./dotnet-install.sh; `
$ENV:PATH="$HOME/.dotnet:$ENV:PATH"; `
dotnet tool install --global dotnet-ef; `
git clone https://github.com/Azure/Commercial-Marketplace-SaaS-Accelerator.git -b 7.4.0 --depth 1; `
cd ./Commercial-Marketplace-SaaS-Accelerator/deployment; `
.\Deploy.ps1 `
 -WebAppNamePrefix "fwd-case-mgmt" `
 -ResourceGroupForDeployment "fwdfedev0rg" `
 -PublisherAdminUsers "regis.anclades@forwardplatform.com,regis.anclades@livestories.com" `
 -Location "West US 2" `
 -TenantID "e34f2bd8-0f32-4d15-a9a1-4b96a16d51e3" `
 -AzureSubscriptionID "e32b6a1d-5183-4d1f-9d68-6f5a7381a724" `
 -LogoURLpng "https://forward.livestories.com/static/media/Forward-Blue.dbec8bc456fbd0f5c40d.png" `
 -LogoURLico "https://forwardplatform.com/wp-content/uploads/2022/10/cropped-forward_ico-32x32.png"
```

```
wget https://dotnet.microsoft.com/download/dotnet/scripts/v1/dotnet-install.sh; `
chmod +x dotnet-install.sh; `
./dotnet-install.sh; `
$ENV:PATH="$HOME/.dotnet:$ENV:PATH"; `
dotnet tool install --global dotnet-ef; `
git clone https://github.com/Azure/Commercial-Marketplace-SaaS-Accelerator.git -b 7.4.0 --depth 1; `
cd ./Commercial-Marketplace-SaaS-Accelerator/deployment; `
.\Deploy.ps1 `
 -Location "East US"
 -WebAppNamePrefix "fwdcasemgmt2" `
 -ResourceGroupForDeployment "fwdcasemgmt2" `
 -PublisherAdminUsers "regis.anclades@forwardplatform.com,regis.anclades@livestories.com" `
 -TenantID "e34f2bd8-0f32-4d15-a9a1-4b96a16d51e3" `
 -AzureSubscriptionID "e32b6a1d-5183-4d1f-9d68-6f5a7381a724"
```

```

git clone https://github.com/Azure/Commercial-Marketplace-SaaS-Accelerator.git -b 7.4.0 --depth 1

cd ./Commercial-Marketplace-SaaS-Accelerator/deployment

.\Deploy.ps1 -WebAppNamePrefix "fwdcasemgmt3" -ResourceGroupForDeployment "fwdcasemgmt3" -PublisherAdminUsers "regis.anclades@forwardplatform.com" -TenantID "e34f2bd8-0f32-4d15-a9a1-4b96a16d51e3" -AzureSubscriptionID "e32b6a1d-5183-4d1f-9d68-6f5a7381a724" -Location "East US"

```

```
      ➡️ Landing Page section:       https://fwdcasemgmt3-portal.azurewebsites.net/
      ➡️ Connection Webhook section: https://fwdcasemgmt3-portal.azurewebsites.net/api/AzureWebhook
      ➡️ Tenant ID:                  e34f2bd8-0f32-4d15-a9a1-4b96a16d51e3
      ➡️ AAD Application ID section: f699f678-bde5-4b3c-b119-8aebea5ab6d8

https://case-management-admin.forwardplatform.com/
https://case-management-saas.forwardplatform.com/api/AzureWebhook
https://case-management-saas.forwardplatform.com/

      ➡️ Landing Page section:       https://case-management-saas.forwardplatform.com/
      ➡️ Connection Webhook section: https://case-management-saas.forwardplatform.com/api/AzureWebhook
      ➡️ Tenant ID:                  e34f2bd8-0f32-4d15-a9a1-4b96a16d51e3
      ➡️ AAD Application ID section: f699f678-bde5-4b3c-b119-8aebea5ab6d8


```