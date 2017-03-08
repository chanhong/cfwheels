```coldfusion
protectedProperties([ properties ])
```
```coldfusion
// In `models/User.cfc`, `firstName` and `lastName` cannot be changed through mass assignment operations like `updateAll()`
<cffunction name="init">
    protectedProperties("firstName,lastName")>
</cffunction>
```