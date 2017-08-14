# Avaliação iOS - Kiddo Labs - Rogerio Hirooka

---
Segue minha versão do projeto teste conforme solicitado. Alterações, notas e outros detalhes estão descritos neste README.


<p align="center">
	<img src="img/ios_logo.png" width="187px">
</p>

### Alterações

- Escolhi não utilizar a API do Guidebox pelos seguintes motivos:
1. Conforme a [documentação mais recente](https://api.guidebox.com/docs/key), não é mais possível solicitar API Keys para uso não-comercial/pessoal:
> The Guidebox API is currently in private beta and we are only accepting commercial applications. Please contact us if your application falls within this criteria. No personal or non-commercial applications are being allowed at this time.

2. A [APIKey utilizada](https://api-public.guidebox.com/v1.43/US/rKJwmLEQB3qOouvHckEwjDrsGqKWpHgE/movies/all/1/10/all/all) no descritivo deste teste já está com seu uso limite esgotado.
```
{"error":"Monthly quota reached for your API key (0 total calls).  Please contact us to request additional API calls."}
```

3. Utilizarei a API do [TheMovieDB.org](https://www.themoviedb.org/), que além de totalmente livre, possui uma [política](https://www.themoviedb.org/terms-of-use) menos restritiva de acesso a seus serviços.

- Tomei a liberdade de criar uma SplashScreen simples com o tema inferido a partir do website da KiddoLabs.

- Os ícones da TabBar estão ligeiramente diferentes pois escolhi utilizar a fonte 'FontAwesome' ao invés de imagens, no intuito de simplificar a expansão futura do App, disponibilizando a coletânea de ícones da fonte e potencialmente economizando espaço e agilizando os futuros desenvolvimentos.

- O projeto está regionalizado no idioma-base Inglês e Português-BR
