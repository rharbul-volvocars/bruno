# Connect Bruno Collection

A collection of API requests for Connect Platform applications supported by L2O team.   
Secrets are stored in the Vault:
- DEV: https://vault.weu-dev.ecpaz.volvocars.biz/ui/vault/secrets
- QA: https://vault.weu-qa.ecpaz.volvocars.biz/ui/vault/secrets
- PROD: https://vault.weu-prod.ecpaz.volvocars.biz/ui/vault/secrets

To easily override `BFF_HOST` variable create a global env with your local instance and disable corresponding value in the env.

## References
- [Bruno Docs](https://docs.usebruno.com/)
- [Customer View BFF OpenAPI](https://backstage.volvocars.biz/catalog/default/api/connect-customer-bff-api/definition)
- [Vehicles Lookup BFF OpenAPI](https://backstage.volvocars.biz/catalog/default/api/connect-vehicles-bff-api/definition)