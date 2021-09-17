All Nuget packages for enitity should be:

  <ItemGroup>
    <PackageReference Include="Microsoft.EntityFrameworkCore.Tools" Version="3.1.3">
      <IncludeAssets>runtime; build; native; contentfiles; analyzers; buildtransitive</IncludeAssets>
      <PrivateAssets>all</PrivateAssets>
    </PackageReference>
    <PackageReference Include="Microsoft.EntityFrameworkCore.Design" Version="3.1.3">
      <IncludeAssets>runtime; build; native; contentfiles; analyzers; buildtransitive</IncludeAssets>
      <PrivateAssets>all</PrivateAssets>
    </PackageReference>
    <PackageReference Include="Microsoft.EntityFrameworkCore.SqlServer" Version="3.1.0" />
    <PackageReference Include="Microsoft.EntityFrameworkCore.Sqlite" Version="3.1.0" />
    <PackageReference Include="Microsoft.VisualStudio.Web.CodeGeneration.Design" Version="3.1.3" />
  </ItemGroup>