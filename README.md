# Infra_DnsDeepDive

## DNS(Domain Name System)
- Three funtions
   + name resolution: translate domain name to IP address
   + name space: 도메인 주소를 어떻게 관리할지에 대한 방법
   + name registration: 도메인을 등록하고 어떻게 유니크하게 있을수 있는지에 대한 것
   
### Name Space
#### Domain name format
1. Root (null) -- Label of null
2. Top-Level Domain(TLD) (.com) -- Zone Apex / Naked Domain, Label
3. Second-Level Domain   (example) -- Zone Apex / Naked Domain, Label
4. Third-Level Domain.   (www) -- , Label
   + can be easly replaced to subdomain like aaa, bbb, ccc
   
- each label is 63 characters long
- Third-Level domain has more then 1
- domain name should be long up to 255 characters.
##### FQDN : fully qualified domain name (www.example.com.)
##### LDH rule 
- letters digits hyphen rule, labels should follow LDH rule.
   + letters: 63 characters long
   + digits: 0-9
   + hyphen: allow hyphen

### DNS Tree
