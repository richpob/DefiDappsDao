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

## 5 Compilar y desplegar el Smart Contract en Remix IDE

Compilación a bytecode y despliegue del código del smart contract en la red de Ethereum para poder interactuar con él.

## 6 Envío de transacciones al Smart Contract con Remix IDE

Para utilizar el smart contract hay que generar transacciones, en este caso realizarás con tu cuenta una transacción de puja a través del método bid.
