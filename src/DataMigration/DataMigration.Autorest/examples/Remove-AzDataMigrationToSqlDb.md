### Example 1: Delete the SQL DB Database Migration resource.
```powershell
Remove-AzDataMigrationToSqlDb -ResourceGroupName tsum38RG -SqlDbInstanceName dmstestsqldb -TargetDbName at_sqldbtrgtps1
```

Delete the SQL DB Database Migration resource.

### Example 2: Delete the SQL DB Database Migration resource even if it is in progress 
```powershell
Remove-AzDataMigrationToSqlDb -ResourceGroupName tsum38RG -SqlDbInstanceName dmstestsqldb -TargetDbName at_sqldbtrgtps1 -Force
```

Forcibly deletes an ongoing Migration to SQL DB by adding the optional "Force" parameter

