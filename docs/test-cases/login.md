# Casos de Teste — Login

## CT-LOGIN-001 — Login com credenciais válidas

### Pré-condição

Usuário cadastrado.

### Passos

1. Acessar a tela de login.
2. Informar e-mail válido.
3. Informar senha válida.
4. Clicar em "Entrar".

### Resultado esperado

O sistema deve autenticar o usuário e direcioná-lo para a área principal.

### Prioridade

Alta

---

## CT-LOGIN-002 — Login com senha inválida

### Passos

1. Acessar a tela de login.
2. Informar e-mail válido.
3. Informar senha incorreta.
4. Clicar em "Entrar".

### Resultado esperado

O sistema deve impedir o acesso e apresentar mensagem de credenciais inválidas.

### Prioridade

Alta

---

## CT-LOGIN-003 — Login com campos vazios

### Passos

1. Acessar a tela de login.
2. Não preencher os campos.
3. Clicar em "Entrar".

### Resultado esperado

O sistema deve informar que os campos obrigatórios precisam ser preenchidos.

### Prioridade

Média
