manIaC es una arquitectura completa desplegada en AWS mediante CloudFormation.
El proyecto crea una VPC con subnets públicas en dos Availability Zones, un Internet Gateway, una instancia EC2 que ejecuta una API REST y un Application Load Balancer que distribuye tráfico de forma segura y altamente disponible.
Todo está definido como código, lo que permite reproducir la infraestructura, escalarla y mantenerla siguiendo buenas prácticas de DevOps y AWS.
