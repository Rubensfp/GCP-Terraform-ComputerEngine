# Bem vindo ao projeto!

Nesse projeto eu utilizo a ferramenta Terraform para provisionar uma 
infraestrutura dentro do cloud provider da Google(GCP).

Em resumo o projeto e simplista e demonstra como criar os seguintes 
recursos dentro da GCP:
- Duas VPC`s que se comunicam entre si
- Regras de Firewall habilitando ICMP e SSH entre as redes
- Duas VM`s (Computer Engine) em regiões diferentes
	> Não utilizei credenciais fixas, no caso do provider ele chamara 
o login no ato do init dentro da ferramenta Terraform.
