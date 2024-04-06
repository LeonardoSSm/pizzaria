Sistema de Gerenciamento de Pedidos em Restaurante
Este é um sistema backend desenvolvido em Node.js com o framework Express.js para gerenciar pedidos em um restaurante. Ele fornece uma API RESTful para as seguintes funcionalidades:

Funcionalidades Principais
Cadastro e Autenticação de Usuários: Os usuários podem se cadastrar no sistema e fazer login para acessar recursos protegidos.

Gerenciamento de Usuários: Os detalhes do usuário autenticado podem ser acessados através da rota /me.

Criação e Listagem de Categorias: Categorias de produtos, como bebidas, entradas, etc., podem ser criadas e listadas.

Criação e Listagem de Produtos por Categoria: Produtos podem ser criados e listados com base em suas categorias.

Gerenciamento de Mesas e Pedidos: Mesas (pedidos) podem ser abertas, fechadas e modificadas. Itens podem ser adicionados e removidos de uma mesa.

Envio e Conclusão de Pedidos: Pedidos podem ser enviados para processamento e concluídos quando estiverem prontos.

Tecnologias Utilizadas
Node.js
Express.js
TypeScript
Prisma (ORM)
PostgreSQL (Banco de Dados)
Multer (Middleware para upload de arquivos)
