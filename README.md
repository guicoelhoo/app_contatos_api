App Contatos
Um aplicativo gerenciador de contatos robusto e moderno, desenvolvido com Expo, React Native e TypeScript, utilizando o Expo Router para uma navegação fluida. O app integra-se perfeitamente a uma API backend em Node.js/MongoDB com suporte a GridFS.

Principais Funcionalidades
Autenticação Segura: Sistema completo de cadastro e login protegido por tokens JWT, com armazenamento criptografado via Expo SecureStore.

CRUD Completo de Contatos: Gestão total de contatos (listar, adicionar, editar e excluir) contemplando campos para nome, e-mail, telefone e endereço.

Upload e Exibição de Fotos: Seleção de imagens direto da galeria através do Expo ImagePicker, com envio para a API (POST /upload) e armazenamento integrado ao GridFS do MongoDB (GET /upload/:id).
