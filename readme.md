# App

Gympass style app

## RFs (Requisitos funcionais)

- [ ] Deve ser possível cadastrar-se;
- [ ] Deve ser possível se autenticar;
- [ ] Deve ser possivel obter o perfil do usuario logado;
- [ ] Deve ser possivel obter o número de check-ins realizados pelo usuário logado;
- [ ] Deve ser possivel o usuário obter seu histórico de check-ins;
- [ ] Deve ser possivel o usuário buscar academias próximas;
- [ ] Deve ser possivel o usuário buscar academias pelo nome;
- [ ] Deve ser possivel o usuário realizar check-in em uma academia;
- [ ] Deve ser possivel validar o check-in do usuário;
- [ ] Deve ser possivel cadastrar uma academia;

## RNs (Regras de Negócios)

- [ ] O usuário não deve poder se cadastrar com um e-mail duplicado;
- [ ] O usuário não pode fazer 2 check-ins no mesmo dia;
- [ ] O usuário não pode fazer check-in se não estiver perto (100m) da academia;
- [ ] O check-in só pode ser validado até 20min após criado;
- [ ] O check-in só pode ser validado por administradores;
- [ ] As academias só podem ser cadastradas pelos administradores;

## RNFs (Requisitos não-funcionais)

- [ ] A senha do usuário deve ser criptografada;
- [ ] Os dados do usuário devem ser armazenados em um banco de dados PostgreSQL;
- [ ] Todas listas de dados precisam estar paginadas com 20 itens por página;
- [ ] O usuário deve ser identificado por um JWT;
