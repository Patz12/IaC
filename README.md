# Proyecto Unidad 3: IaC y Git

## Progreso

- Componetes de red
  - [x] VPC
  - [x] Subredes
  - [x] Internet Gateway
  - [x] NAT Gateway
  
- EC2
  - [x] Web server
  - [ ] Load Balancer
  - [ ] Autoscaling groups
  - [x] Security groups

- Opcionales
  - [x] AMIs
  - [x] Cuenta específica para IaC

### Referencias

- [Anatomia de un template](https://docs.aws.amazon.com/AWSCloudFormation/latest/UserGuide/template-anatomy.html)
- [Parametros](https://docs.aws.amazon.com/AWSCloudFormation/latest/UserGuide/parameters-section-structure.html)
- [Outputs](https://docs.aws.amazon.com/AWSCloudFormation/latest/UserGuide/outputs-section-structure.html)
- [Ejemplo de networking](https://docs.aws.amazon.com/codebuild/latest/userguide/cloudformation-vpc-template.html)
- [Ejemplo de autoscaling y loadbalancer](https://docs.aws.amazon.com/AWSCloudFormation/latest/UserGuide/quickref-autoscaling.html)

## Instrucciones

- **Crear la Stack**

```bash
aws cloudformation deploy --template-file '.Infrastructura AWS.yaml' --stack-name Proyecto3
```

- **Destruir la Stack**

```bash
aws cloudformation delete-stack --stack-name Proyecto3
```
