<div align="center">
  <h1>
    MY_WEATHER_APP
  </h1>

 </div>

<p>&nbsp;&nbsp;&nbsp;&nbsp;Este aplicativo de clima foi desenvolvido utilizando HTML, CSS e JavaScript. Permite aos usuários inserir a cidade desejada para obter informações meteorológicas atuais. O objetivo é proporcionar uma experiência do usuário simplificada para acesso rápido a dados meteorológicos essenciais. Este projeto também serve como uma oportunidade de aprendizado para tecnologias da web e integração de APIs de clima.</p>

<p>&nbsp;&nbsp;&nbsp;&nbsp;Por questões de segurança e para garantir a melhor experiência possível para todos os usuários, a chave de API não foi incluída diretamente no projeto. Em vez disso, para configurar a chave de API, siga os passos detalhados na seção de 'Configuração da Chave de API do OpenWeatherMap' desta documentação para gerar e inserir sua própria chave de API. É sempre importante proteger e ocultar suas chaves de API para evitar acessos não autorizados e manter a segurança dos dados. Desta forma, cada usuário terá controle sobre o acesso aos dados meteorológicos e manteremos a integridade do serviço para todos. Agradeço antecipadamente por seguir estas orientações e contribuir para a segurança e privacidade dos dados.</p>

--- 

## Configuração da Chave de API do OpenWeatherMap

Para usar este projeto, você precisará de uma chave de API do OpenWeatherMap. Siga as etapas abaixo para configurar sua chave de API:

1. **Crie uma conta no OpenWeatherMap**: Se você ainda não tiver uma conta, vá para [OpenWeatherMap](https://openweathermap.org/) e crie uma conta gratuita.
   
2. **Faça login na sua conta OpenWeatherMap**: Após criar sua conta, faça login no OpenWeatherMap.

3. **Gere sua chave de API**: Depois de fazer login, vá para "API Keys" e clique em "Create key". Dê um nome à sua chave e clique em "Generate".

4. **Copie sua chave de API**: Após gerar sua chave de API, copie-a para a área de transferência.

   *Caso você já tenha uma chave de API criada e enviada por e-mail*, você pode copiá-la do e-mail e seguir para a etapa 5.

5. **Uso da Chave de API no Projeto**

Depois de gerar sua chave de API do OpenWeatherMap, você precisará inseri-la no código-fonte do projeto. Siga estas etapas para adicionar sua chave de API:

- Abra o arquivo `script.js` no seu editor de código preferido.
- Procure pela variável `apiKey` no arquivo `script.js`.
- Substitua `'SUACHAVEDEAPIAQUI'` pela chave de API que você copiou anteriormente.

Exemplo:

```javascript
const apiKey = 'SUA_CHAVE_DE_API_AQUI';
```

---