# Revit.References

References to Revit 2027 to 2022 assemblies.

### Version

``` xml
<PropertyGroup Condition=" '$(Configuration)|$(Platform)' == '2017|AnyCPU' ">
    <TargetFrameworkVersion>v4.6</TargetFrameworkVersion>
    <DebugSymbols>true</DebugSymbols>
    <OutputPath>bin\$(Configuration)\</OutputPath>
    <DefineConstants>TRACE;Revit2017</DefineConstants>
    <FileAlignment>4096</FileAlignment>
    <DebugType>Full</DebugType>
    <PlatformTarget>x64</PlatformTarget>
    <LangVersion>7.3</LangVersion>
    <CodeAnalysisRuleSet>MinimumRecommendedRules.ruleset</CodeAnalysisRuleSet>
  </PropertyGroup>
  <PropertyGroup Condition=" '$(Configuration)|$(Platform)' == '2018|AnyCPU' ">
    <TargetFrameworkVersion>v4.6</TargetFrameworkVersion>
    <DebugSymbols>true</DebugSymbols>
    <OutputPath>bin\$(Configuration)\</OutputPath>
    <DefineConstants>TRACE;Revit2018</DefineConstants>
    <FileAlignment>4096</FileAlignment>
    <DebugType>Full</DebugType>
    <PlatformTarget>x64</PlatformTarget>
    <LangVersion>7.3</LangVersion>
    <CodeAnalysisRuleSet>MinimumRecommendedRules.ruleset</CodeAnalysisRuleSet>
  </PropertyGroup>
  <PropertyGroup Condition=" '$(Configuration)|$(Platform)' == '2019|AnyCPU' ">
    <TargetFrameworkVersion>v4.7</TargetFrameworkVersion>
    <DebugSymbols>true</DebugSymbols>
    <OutputPath>bin\$(Configuration)\</OutputPath>
    <DefineConstants>TRACE;Revit2019</DefineConstants>
    <FileAlignment>4096</FileAlignment>
    <DebugType>Full</DebugType>
    <PlatformTarget>x64</PlatformTarget>
    <LangVersion>7.3</LangVersion>
    <CodeAnalysisRuleSet>MinimumRecommendedRules.ruleset</CodeAnalysisRuleSet>
  </PropertyGroup>
  <PropertyGroup Condition="'$(Configuration)|$(Platform)' == '2020|AnyCPU'">
    <TargetFrameworkVersion>v4.7</TargetFrameworkVersion>
    <OutputPath>bin\$(Configuration)\</OutputPath>
    <DefineConstants>TRACE;Revit2020</DefineConstants>
    <DebugSymbols>true</DebugSymbols>
    <FileAlignment>4096</FileAlignment>
    <DebugType>Full</DebugType>
    <PlatformTarget>x64</PlatformTarget>
    <LangVersion>7.3</LangVersion>
    <CodeAnalysisRuleSet>MinimumRecommendedRules.ruleset</CodeAnalysisRuleSet>
  </PropertyGroup>
  <PropertyGroup Condition="'$(Configuration)|$(Platform)' == '2021|AnyCPU'">
    <TargetFrameworkVersion>v4.8</TargetFrameworkVersion>
    <OutputPath>bin\$(Configuration)\</OutputPath>
    <DefineConstants>TRACE;Revit2021</DefineConstants>
    <DebugSymbols>true</DebugSymbols>
    <FileAlignment>4096</FileAlignment>
    <DebugType>Full</DebugType>
    <PlatformTarget>x64</PlatformTarget>
    <LangVersion>7.3</LangVersion>
    <CodeAnalysisRuleSet>MinimumRecommendedRules.ruleset</CodeAnalysisRuleSet>
  </PropertyGroup>
  <PropertyGroup Condition="'$(Configuration)|$(Platform)' == '2022|AnyCPU'">
    <TargetFrameworkVersion>v4.8</TargetFrameworkVersion>
    <OutputPath>bin\$(Configuration)\</OutputPath>
    <DefineConstants>TRACE;Revit2022</DefineConstants>
    <DebugSymbols>true</DebugSymbols>
    <FileAlignment>4096</FileAlignment>
    <DebugType>Full</DebugType>
    <PlatformTarget>x64</PlatformTarget>
    <LangVersion>7.3</LangVersion>
    <CodeAnalysisRuleSet>MinimumRecommendedRules.ruleset</CodeAnalysisRuleSet>
  </PropertyGroup>
  <PropertyGroup Condition="'$(Configuration)|$(Platform)' == 'Debug|AnyCPU'">
    <TargetFrameworkVersion>v4.8</TargetFrameworkVersion>
    <DebugSymbols>true</DebugSymbols>
    <OutputPath>bin\Debug\</OutputPath>
    <DefineConstants>DEBUG;TRACE;Revit2021</DefineConstants>
    <FileAlignment>4096</FileAlignment>
    <DebugType>Full</DebugType>
    <PlatformTarget>x64</PlatformTarget>
    <LangVersion>7.3</LangVersion>
    <CodeAnalysisRuleSet>MinimumRecommendedRules.ruleset</CodeAnalysisRuleSet>
  </PropertyGroup>
  <PropertyGroup Condition="'$(Configuration)|$(Platform)' == 'Release|AnyCPU'">
    <TargetFrameworkVersion>v4.8</TargetFrameworkVersion>
    <DebugSymbols>true</DebugSymbols>
    <OutputPath>bin\Release\</OutputPath>
    <DefineConstants>TRACE;Revit2021</DefineConstants>
    <FileAlignment>4096</FileAlignment>
    <DebugType>Full</DebugType>
    <PlatformTarget>x64</PlatformTarget>
    <LangVersion>7.3</LangVersion>
    <CodeAnalysisRuleSet>MinimumRecommendedRules.ruleset</CodeAnalysisRuleSet>
  </PropertyGroup>
```

### References
``` xml
  <ItemGroup>
    <Reference Include="RevitAPI">
      <HintPath>..\references\RevitAPI\$(Configuration)\RevitAPI.dll</HintPath>
      <Private>False</Private>
    </Reference>
    <Reference Include="RevitAPIUI">
      <HintPath>..\references\RevitAPI\$(Configuration)\RevitAPIUI.dll</HintPath>
      <Private>False</Private>
    </Reference>
    <Reference Include="AdWindows">
      <HintPath>..\references\RevitAPI\$(Configuration)\AdWindows.dll</HintPath>
      <Private>False</Private>
    </Reference>
    <Reference Include="UIFramework">
      <HintPath>..\references\RevitAPI\$(Configuration)\UIFramework.dll</HintPath>
      <Private>False</Private>
    </Reference>
  </ItemGroup>
```

---


Do you like this library? Please [star this project on GitHub](https://github.com/ricaun/Revit.References/stargazers)!

[Video]: https://youtu.be/DCWenLzVuss
[VideoIma]: https://img.youtube.com/vi/DCWenLzVuss/hqdefault.jpg