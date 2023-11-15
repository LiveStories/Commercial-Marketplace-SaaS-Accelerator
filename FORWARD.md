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