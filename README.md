# BD-FUNCTIONS


Nesta atividade utilizamos as funçoes.

## ETAPA 1-1:
 Criação das Tabelas:

    CREATE TABLE Pedidos(
    IDPedido INT AUTO_INCREMENT PRIMARY KEY,
    DataPedido DATETIME,
    NomeCliente VARCHAR(100)
    );

    INSERT INTO Pedidos(DataPedido, NomeCliente) VALUES
    (NOW(), 'Cliente 1'),
    (NOW(),'Cliente 2'),
    (NOW(),	'Cliente 3');

    ```
![exer1](https://github.com/Ig0rFA/BD-TRIGGER/blob/main/BD-TRIGGER/Pedidos%201.png).
