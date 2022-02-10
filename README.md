# IaC y Git

## Progreso

- Componetes de red
  - [x] VPC
  - [x] Subredes
  - [x] Internet Gateway
  - [x] NAT Gateway
  
- EC2
  - [x] Web server
  - [x] Load Balancer
  - [x] Autoscaling groups
  - [x] Security groups

- Opcionales
  - [x] AMIs
  - [x] Cuenta específica para IaC
  - [ ] Diagrama de la infraestructura

### Referencias

- [Anatomia de un template](https://docs.aws.amazon.com/AWSCloudFormation/latest/UserGuide/template-anatomy.html)
- [Parametros](https://docs.aws.amazon.com/AWSCloudFormation/latest/UserGuide/parameters-section-structure.html)
- [Outputs](https://docs.aws.amazon.com/AWSCloudFormation/latest/UserGuide/outputs-section-structure.html)
- [Ejemplo de networking](https://docs.aws.amazon.com/codebuild/latest/userguide/cloudformation-vpc-template.html)
- [Ejemplo de autoscaling y loadbalancer](https://docs.aws.amazon.com/AWSCloudFormation/latest/UserGuide/quickref-autoscaling.html)

## Instrucciones

- **Crear la Stack**

```bash
aws cloudformation deploy --template-file './InfrastructuraAWS.yaml' --stack-name IaC
```

- **Destruir la Stack**

```bash
aws cloudformation delete-stack --stack-name IaC
```
