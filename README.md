# PERC721 Sample

This is a sample ERC721 contract that implements Swisstronic's account check. To use private view functions like `ownerOf` and `balanceOf` require that the user be authorized.

To authorize a user to access these functions, you can use the modifier `onlyAuthorized` via the `grantAcccess()` and `revokeAccess()` functions.