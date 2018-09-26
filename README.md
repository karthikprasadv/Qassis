# Qassis
# Assigning filepath variable for project to build
if($env:Project -eq 'BCStagingToPODS'){
   $Filepath="$env:WORKSPACE\$env:Project\$env:Project\"
   $DeployFolder="$env:Project"
   
}Elseif($env:Project -eq 'CCToPODS'){
    $Filepath="$env:WORKSPACE\$env:Project\$env:Project\"
    $DeployFolder="$env:Project"
   
}Elseif($env:Project -eq 'CLUEClaimsDataPullVerisk'){
    $Filepath="$env:WORKSPACE\Claims\Clue\$env:Project\"
    $DeployFolder="Claims"

}Elseif($env:Project -eq 'DailyPCStagingToPODS'){
    $Filepath="$env:WORKSPACE\$env:Project\$env:Project\"
    $DeployFolder="StagingToPODS"

}Elseif($env:Project -eq 'DailyPODStoEDW'){
    $Filepath="$env:WORKSPACE\$env:Project\$env:Project\"
    $DeployFolder="PODSToEDW"

}Elseif($env:Project -eq 'RoadsideAssistance'){
    $Filepath="$env:WORKSPACE\Claims\RoadsideAssistance\RoadsideAssistance\"
    $DeployFolder="Claims"

}Elseif($env:Project -eq 'DataValidation'){
    $Filepath="$env:WORKSPACE\DataValidation\DataValidation\"
    $DeployFolder="$env:Project"

}Elseif($env:Project -eq 'ExternalToPODS'){
    $Filepath="$env:WORKSPACE\$env:Project\$env:Project\"
    $DeployFolder="$env:Project"

}Elseif($env:Project -eq 'Extracts'){
    $Filepath="$env:WORKSPACE\$env:Project\$env:Project\$env:Project\"
    $DeployFolder="$env:Project"

}Elseif($env:Project -eq 'MarketingDataSetFTP'){
    $Filepath="$env:WORKSPACE\Extracts\$env:Project\"
    $DeployFolder="Extracts"

}Elseif($env:Project -eq 'ImportPostgres'){
    $Filepath="$env:WORKSPACE\$env:Project\"
    $DeployFolder="ImportPostgres"

}Elseif($env:Project -eq 'INSProdToStaging'){
    $Filepath="$env:WORKSPACE\$env:Project\"
    $DeployFolder="PorductionToStaging"

}Elseif($env:Project -eq 'INSTransactionToPODS'){
    $Filepath="$env:WORKSPACE\$env:Project\"
    $DeployFolder="$env:Project"

}Elseif($env:Project -eq 'MAS500'){
    $Filepath="$env:WORKSPACE\$env:Project\$env:Project\"
    $DeployFolder="$env:Project"

}Elseif($env:Project -eq 'PCProdToStaging'){
    $Filepath="$env:WORKSPACE\$env:Project\"
    $DeployFolder="PorductionToStaging"

}Elseif($env:Project -eq 'PCProdToStagingQuotes'){
    $Filepath="$env:WORKSPACE\$env:Project\PCProdToStagingQuote\"
    $DeployFolder="PorductionToStaging"

}Elseif($env:Project -eq 'PCQuoteToPODS'){
    $Filepath="$env:WORKSPACE\$env:Project\"
    $DeployFolder="StagingToPODS"

}Elseif($env:Project -eq 'PCStagingToPODS'){
    $Filepath="$env:WORKSPACE\$env:Project\$env:Project\"
    $DeployFolder="StagingToPODS"

}Elseif($env:Project -eq 'PCTransactionStagingToPODS'){
    $Filepath="$env:WORKSPACE\PCTransactionToPODS\PCTransactionToPODS\"
    $DeployFolder="StagingToPODS"

}Elseif($env:Project -eq 'PODS To EDW'){
    $Filepath="$env:WORKSPACE\$env:Project\$env:Project\"
    $DeployFolder="PODSToEDW"

}Elseif($env:Project -eq 'PriceComparisonExtractsAndInvoicing'){
    $Filepath="$env:WORKSPACE\Sandbox Marketing\$env:Project\$env:Project"
    $DeployFolder="Sandbox Marketing"    

}Elseif($env:Project -eq 'Sandbox Pricing'){
    $Filepath="$env:WORKSPACE\Pricing\"
    $DeployFolder="$env:Project"

}Elseif($env:Project -eq 'HLDI Data Extract'){
    $Filepath="$env:WORKSPACE\Pricing\$env:Project\$env:Project\"
    $DeployFolder="Pricing"

}Elseif($env:Project -eq 'IBNRFactorUpdate'){
    $Filepath="$env:WORKSPACE\Pricing\$env:Project\$env:Project\"
    $DeployFolder="$env:Project"

}Elseif($env:Project -eq 'HomesiteLifeInsuranceDataLoad'){
    $Filepath="$env:WORKSPACE\Product\$env:Project\"
    $DeployFolder="Product"

}Elseif($env:Project -eq 'RegulatoryReporting'){
    $Filepath="$env:WORKSPACE\$env:Project\"
    $DeployFolder="$env:Project"

}Elseif($env:Project -eq 'Reports and Aggregation'){
    $Filepath="$env:WORKSPACE\$env:Project\$env:Project\"
    $DeployFolder="$env:Project"

}Elseif($env:Project -eq 'AutomatedSpend'){
    $Filepath="$env:WORKSPACE\Sandbox Marketing\$env:Project\$env:Project\"
    $DeployFolder="Sandbox Marketing"

}Elseif($env:Project -eq 'BrokerFiles'){
    $Filepath="$env:WORKSPACE\Sandbox Marketing\$env:Project\$env:Project\"
    $DeployFolder="Sandbox Marketing"

}Elseif($env:Project -eq 'ChannelAttributionModels'){
    $Filepath="$env:WORKSPACE\Sandbox Marketing\$env:Project\$env:Project\"
    $DeployFolder="Sandbox Marketing"

}Elseif($env:Project -eq 'CompareNowSalesDataPull'){
    $Filepath="$env:WORKSPACE\Sandbox Marketing\CompareExtracts\$env:Project\"
    $DeployFolder="Sandbox Marketing"

}Elseif($env:Project -eq 'DataMover'){
    $Filepath="$env:WORKSPACE\Sandbox Marketing\$env:Project\$env:Project\"
    $DeployFolder="Sandbox Marketing"

}Elseif($env:Project -eq 'GoogleBigQuery'){
    $Filepath="$env:WORKSPACE\Sandbox Marketing\$env:Project\$env:Project\"
    $DeployFolder="Sandbox Marketing"

}Elseif($env:Project -eq 'TotalQuotes'){
    $Filepath="$env:WORKSPACE\Sandbox Marketing\$env:Project\"
    $DeployFolder="Sandbox Marketing"

}Elseif($env:Project -eq 'VendorFileImport'){
    $Filepath="$env:WORKSPACE\Sandbox Marketing\$env:Project\$env:Project\$env:Project\"
    $DeployFolder="Sandbox Marketing"

}Elseif($env:Project -eq 'VINISORebuild'){
    $Filepath="$env:WORKSPACE\SpecialOps\Verisk VIN ISO Rebuild\$env:Project\"
    $DeployFolder="SpecialOps"
}

Write-Output $Filepath

if($env:Env -eq 'qa'){
    $SSISEnviroment = "$env:Env"
 }Elseif ($env:Env -eq 'prd'){
    $SSISEnviroment = "Prod"
 }
 Else { $SSISEnviroment = "Dev"}

#- add the double backslash to escape the backslash in the filepath so one remains when it is read back into the process
$Filepath=$Filepath -replace ("\\", "\\\")

# Write the filepath to the file that it can be read back into the jenkins script and used in other parts of the process
"FilepathNew=$Filepath" | Out-File env.properties -Force -Encoding ASCII
"DeployFolder=$DeployFolder" | Out-File env2.properties -Force -Encoding ASCII
"SSISEnvironment=$SSISEnviroment" | Add-Content env2.properties
