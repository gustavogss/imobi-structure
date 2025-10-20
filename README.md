# imobi-structure 

**Contribuição de Gustavo Souza**  

**Estrutura JSON pronta para sites de imobiliárias**  

Este repositório contém modelos JSON para Pods, taxonomias e campos personalizados, prontos para serem importados no WordPress com o plugin **Pods**.  
A ideia é **facilitar a criação de sites de imobiliárias**, permitindo que você importe apenas os Pods que precisa, funcionando como boilerplate.

---

## Pods incluídos

### 1. Imóveis (`imoveis.json`)
- Campos: preço, área total, área útil, quartos, banheiros, garagem, descrição curta.
- Comodidades: piscina, playground, academia, salão de festas, churrasqueira, quadra de futebol, sauna, energia solar.
- Financeiro: taxa de condomínio, IPTU.
- Endereço completo: rua, número, bairro, CEP.
- Relacionamento: corretor responsável (Pod Corretores).
- Taxonomias: tipo de imóvel, status, localização (cidade), faixa de preço.

### 2. Corretores (`corretores.json`)
- Campos: nome, telefone, e-mail, CRECI, foto.
- Relacionamento: usado no Pod Imóveis.

### 3. Administradores (`administradores.json`)
- Campos: usuário, e-mail, nível de acesso (Admin, Editor, Gerente).
- Não público, para controle interno.

### 4. Usuários – Alugar/Vender (`usuarios_cliente.json`)
- Campos: nome, e-mail, telefone, tipo de operação (Alugar/Vender), imóveis relacionados, observações.

### 5. Usuários – Comprar/Vender (`usuarios_comprador.json`)
- Campos: nome, e-mail, telefone, tipo de operação (Comprar/Vender), preferências do imóvel (cidade, faixa de preço, quartos mínimos), observações.

---

## Como usar

1. Faça o download do repositório.
2. No WordPress, instale e ative o plugin [Pods](https://pods.io/).
3. Vá em **Pods Admin → Import/Export → Import JSON**.
4. Selecione o JSON do Pod que deseja importar.
5. Todos os campos, taxonomias e relacionamentos estarão prontos para uso.

---

## Contribuições

Contribuições são bem-vindas!  
Se quiser adicionar novos campos, taxonomias ou melhorar a estrutura, faça um fork e envie um pull request.

---

## Licença

MIT License © 2025

---

 Feito com 💚 por Gustavo Souza
