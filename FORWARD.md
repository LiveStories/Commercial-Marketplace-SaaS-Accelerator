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
 -WebAppNamePrefix "fwd-case-mgmt" `
 -ResourceGroupForDeployment "fwdfedev0rg" `
 -PublisherAdminUsers "regis.anclades@forwardplatform.com,regis.anclades@livestories.com" `
 -Location "West US 2" `
 -TenantID "e34f2bd8-0f32-4d15-a9a1-4b96a16d51e3" `
 -AzureSubscriptionID "e32b6a1d-5183-4d1f-9d68-6f5a7381a724"

 Starting SaaS Accelerator Deployment...
🔑 Tenant provided: e34f2bd8-0f32-4d15-a9a1-4b96a16d51e3
🔑 Azure Subscription provided: e32b6a1d-5183-4d1f-9d68-6f5a7381a724
🔑 Azure Subscription 'e32b6a1d-5183-4d1f-9d68-6f5a7381a724' selected.
🔑 Creating Fulfilment API App Registration
   🔵 FulfilmentAPI App Registration created.
      ➡️ Application ID: f27af004-1c45-4587-bc9c-7491f2cdaa8e
      ➡️ App Secret: M6l8Q~Cnoampx~k4H5Z0agzmlWGnph3bkNnkocsK
🔑 Creating Landing Page SSO App Registration
   🔵 Landing Page SSO App Registration created.
      ➡️ Application Id: fdcf559d-a9d6-416a-893f-9ffc8cbe0e29
```