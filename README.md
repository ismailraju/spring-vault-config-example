# spring-vault-config-example


# run vault:
vault.exe server -dev   --dev-root-token-id 00000000-0000-0000-0000-000000000000

create new cmd then:
```set VAULT_ADDR=http://127.0.0.1:8200```


# write : 
vault kv put secret/spring-vault-config-example javatechie.username=Basant javatechie.password=Basant_pwd

# read : 
vault kv get secret/spring-vault-config-example

# Delete: 
vault kv delete secret/spring-vault-config-example
