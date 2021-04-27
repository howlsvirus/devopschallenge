# devopschallenge
Crear una instancia EC2 debajo de un balanceador de carga en AWS.

Instrucciones

    1. Usando Cloudformation se crear una VPC la cual tiene dos subnets, una privada y una pública usando el archivo:
        "0_vpc_with_private_and_public_subnet.yaml"
    2. Para el punto #2, podemos usar el archivo:
        "1_ec2_with_nginx.yaml"
       El cual crea una instancia EC2 dentro de la subnet privada y a su vez, instalar y configura nginx usando ansible.
    3. Durante la creacion de la instancia, se crea un archivo donde se muestra la ip local:
        "localIP.txt"
    <!-- Crear un balanceador en la subnet pública.
    Agregar la instancia EC2 al balanceador. -->
