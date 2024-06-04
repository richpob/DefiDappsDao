# DefiDappsDao
Proyecto para el Sptint 1 , 2 y 3

En este sprint instalarás tú mismo un Smart Contract en una testnet de Ethereum en concreto, Sepolia*.  El Smart Contract representa una subasta de una obra de arte en la que cualquier usuario con una cuenta de Ethereum puede realizar una puja para hacerse con su propiedad. A continuación se muestran los diferentes pasos que debes seguir. Cada uno de los siguientes puntos han sido explicados y realizados en los diferentes temas teóricos.

# Sprint 1
## 1 Instalar Metamask

Es esencial disponer de un Wallet en el que podamos crear y gestionar nuestras cuentas de Ethereum para enviar transacciones a la red.

En nuestro caso usaremos una cuenta actual que tiene Ether en la TestNet Sepolia:

![image](https://github.com/richpob/DefiDappsDao/assets/133718913/c24c49e7-6a00-4650-993f-42a941d49254)

Usaremos el complemento de MetaMask en Chrome

![image](https://github.com/richpob/DefiDappsDao/assets/133718913/571fd9c0-0357-44c8-9619-48960efad656)


## 2 Crear una cuenta de Ethereum a través de Metamask

Para crear transacciones en Ethereum hay que hacerlo a través de una cuenta. La cuenta que usaremos para este Sprint es 0xc83273f025ecEd0317f52DfE26d95C4638a10D7E


## 3 Obtener Ether a través de un faucet

Para desplegar contratos y enviar transacciones a la red, es necesario gastar Gas. A través de un faucet o grifo se puede obtener Ether para redes de prueba. Últimamente, los faucets se han protegido frente a los bots que demandan continuamente Ether de prueba y, por lo tanto, ahora la mayoría exigen tener algo de saldo en la mainnet para poder pedir Ether de prueba. Ni para la realización de este sprint ni para el de ningún otro, es necesario adquirir Ether en la Mainnet pero por si por algún casual, dispones de una cantidad de Ether en la mainnet que te permite pedir Ether de prueba, utiliza el siguiente faucet de Alchemy para hacerlo https://www.alchemy.com/faucets/ethereum-sepolia. Si por el contrario, no dispones de saldo en la Mainnet, escribe tu dirección pública de tu cuenta en el debate del sprint o en el foro de dudas, para que te pueda hacer una transferencia de Ether de prueba (o pídele saldo a algún compañero).

![image](https://github.com/richpob/DefiDappsDao/assets/133718913/97c6422e-2ec3-44a2-b517-994d72f29232)

TX : xeade6f9d5876e3621cedeff2003d44cee93e90df0f575c30750a1f30ec8c864a

https://sepolia.etherscan.io/tx/0xeade6f9d5876e3621cedeff2003d44cee93e90df0f575c30750a1f30ec8c864a

![image](https://github.com/richpob/DefiDappsDao/assets/133718913/efc802e1-6f23-4755-ac90-18cbe0615c22)

![image](https://github.com/richpob/DefiDappsDao/assets/133718913/c14e3194-b37b-4381-92f1-137ecf52ab50)




## 4 Copiar el Smart Contract en Remix IDE

Generación de un archivo con extensión .sol con el contenido del smart contract en Remix IDE. El código del smart contract puedes encontrarlo aquí: https://github.com/CesRC/auction-example-solidity

Fichero Auction.sol
![image](https://github.com/richpob/DefiDappsDao/assets/133718913/b3582dc8-3b29-45de-973a-fcdf89213b42)


Se compila con version 0.0.6.9 menor que la que se exige
![image](https://github.com/richpob/DefiDappsDao/assets/133718913/2349b978-d1e8-446f-bc01-3431d2477390)




## 5 Compilar y desplegar el Smart Contract en Remix IDE

Compilación a bytecode y despliegue del código del smart contract en la red de Ethereum para poder interactuar con él.

Despliegue en TestNet Sepolia usando Metamask

![image](https://github.com/richpob/DefiDappsDao/assets/133718913/a1ee962c-85e6-4fd0-875a-b6f919e1584c)

Deploy:
![image](https://github.com/richpob/DefiDappsDao/assets/133718913/5a5a8871-d34a-4142-88fd-937469d54b4c)

![image](https://github.com/richpob/DefiDappsDao/assets/133718913/abe1dd29-19f6-4ec5-9426-f97a2d222df6)

![image](https://github.com/richpob/DefiDappsDao/assets/133718913/4dac4faa-9533-4fdf-bdaa-51c1fdd2ab32)

TX en xplorer :
https://sepolia.etherscan.io/tx/0x5a975c32699cb931d39bda34960ceacc4a24f60ac655bd21488f6c2502a785b2

URL Contrato: 
https://sepolia.etherscan.io/address/0x33ee37bfe442e0c891a0a951ca7e439e2c68aebf

Verificación y Publicar contrato:
![image](https://github.com/richpob/DefiDappsDao/assets/133718913/d82be0d3-3130-44b1-8619-ce7ba508ac61)

![image](https://github.com/richpob/DefiDappsDao/assets/133718913/fc15dbd2-bfe0-4153-841d-ad8e804f394d)

Resultado verificación y publicación

![image](https://github.com/richpob/DefiDappsDao/assets/133718913/7348cb64-d076-4c82-b26f-7ecb5ff4a03f)

![image](https://github.com/richpob/DefiDappsDao/assets/133718913/871efb62-d65f-46c9-a300-11f13872deaf)

Metodos de consultas READ
![image](https://github.com/richpob/DefiDappsDao/assets/133718913/5c87ed59-59e0-404b-a0d4-8d8adf6ed7ef)


Metodos de Escritura : Write

![image](https://github.com/richpob/DefiDappsDao/assets/133718913/4553808f-4ace-471f-a696-a640cd18dd09)





## 6 Envío de transacciones al Smart Contract con Remix IDE

Para utilizar el smart contract hay que generar transacciones, en este caso realizarás con tu cuenta una transacción de puja a través del método bid.

Transacciones del Contrato creado:

https://sepolia.etherscan.io/address/0x33ee37bfe442e0c891a0a951ca7e439e2c68aebf

Ejecuta metodo Bid:
![image](https://github.com/richpob/DefiDappsDao/assets/133718913/5b280809-1dd8-4e6e-b9cf-2437ef4fb78c)

![image](https://github.com/richpob/DefiDappsDao/assets/133718913/2eb080e1-c044-43f8-9884-41ea0912bcf6)


![image](https://github.com/richpob/DefiDappsDao/assets/133718913/9145030c-fdde-4fa5-aaf7-837356a5c9e5)

![image](https://github.com/richpob/DefiDappsDao/assets/133718913/260d5d93-63cd-4ce7-9953-cf70823fb467)


![image](https://github.com/richpob/DefiDappsDao/assets/133718913/1521aceb-7763-4deb-b51b-1f7dee1eb43d)

