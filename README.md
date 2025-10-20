# imobi-structure

**Estrutura JSON pronta para sites de imobiliárias**  

O `imobi-structure` é um conjunto de modelos JSON que podem ser usados como **boilerplate** para Pods, taxonomia e outros elementos em sites de imobiliárias. A ideia é agilizar a criação de novos sites, permitindo que você **importe essa estrutura pronta** sempre que precisar iniciar um projeto.

---

## Funcionalidades

- Estrutura organizada de **Pods** para custom post types.
- Taxonomias pré-definidas como:
  - Tipo de imóvel
  - Status do imóvel
  - Localização
  - Faixa de preço
- Estrutura de campos personalizada para:
  - Informações de imóveis (quartos, banheiros, área, etc.)
  - Galeria de imagens
  - Contato do corretor
- Fácil importação em qualquer projeto WordPress que use Pods.
- Reduz o tempo de setup inicial, funcionando como **boilerplate JSON**.

---

## Como usar

1. Faça o download do arquivo JSON do `imobi-structure`.
2. No WordPress, instale e ative o plugin [Pods](https://pods.io/).
3. Vá em **Pods Admin → Import/Export → Import JSON**.
4. Selecione o arquivo JSON do `imobi-structure` e clique em **Importar**.
5. Todos os Custom Post Types, taxonomias e campos personalizados estarão prontos para uso.

---

## Estrutura incluída

```json
{
  "pods": [
    {
      "name": "Imóveis",
      "fields": ["Título", "Descrição", "Preço", "Quartos", "Banheiros", "Área", "Galeria"]
    }
  ],
  "taxonomies": [
    "Tipo de Imóvel",
    "Status do Imóvel",
    "Localização",
    "Faixa de Preço"
  ]
}
