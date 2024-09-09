# spring-as-saml-service-provider

1. Set Liferay (port 8080) as Identity Provider
- EntityId: liferay-idp
2. Add SpringApp (port 8081) as a new SP
- EntityId: http://localhost:8081/saml2/service-provider-metadata/liferay-idp
-  SP metadata: http://localhost:8081/saml2/service-provider-metadata/liferay-idp
3. Download liferay metadata.xml from http://localhost:8080/c/portal/saml/metadata.xml and save the file into resources/metadata