Olá, sou o Lucas 👋

Desenvolvedor Android Nativo especializado em **Kotlin** e **Jetpack Compose**. Domínio em fluxos reativos e assíncronos com **Coroutines** e **Flow**, além de sólida prática em **Testes Unitários** (**Mocks, Fakes e Turbine**). Foco em arquiteturas escaláveis (**MVVM, Clean Architecture**) e injeção de dependência com **Hilt**.

## 👨‍💻 Tech Stack
- Linguagem: Kotlin
- UI: Jetpack Compose
- Arquitetura: MVVM, Clean Architecture, SOLID
- DI: Hilt (Dagger)
- Assincronia: Coroutines & Flow
- Rede/Dados: Retrofit, OkHttp & Room
- Testes: Unit Testing (Turbine, MockK, Fake Objects)

## 🌱 Currently learning
 - Firebase: Implementação de Autenticação (Google/Email), Cloud Firestore para persistência em nuvem e Crashlytics para monitoramento de estabilidade.

## 🚀 Projetos em destaque
Confira meus repositórios fixados abaixo 👇

### 🎲 LivToys · [Google Play](https://play.google.com/store/apps/details?id=com.lucasdev.livplay)
App oficial de uma luderia, publicado na Google Play, com mesas de jogo, acervo, sorteios e notificações em tempo real.

* Push Notifications Ponta a Ponta: Firebase Cloud Messaging no app e Cloud Functions em TypeScript, disparadas por eventos do Firestore, para avisar sobre novas mesas, participantes, cupons e resultados de sorteios.
* Arquitetura & Clean Code: Estrutura em MVVM e Clean Architecture com Hilt, qualifiers customizados (@DispatcherIO, @ApplicationScope) e mappers centralizados entre as camadas.
* Local-First & Tempo Real: Room como cache local, sincronizado com listeners do Firestore encapsulados em callbackFlow. A tela abre com os dados salvos e se atualiza ao vivo.
* Integração com API Externa: Consumo da API do BoardGameGeek (XML) com Retrofit, kotlinx.serialization e xmlutil, para montar o acervo com capas e metadados oficiais.
* Segurança & Modern Android Standards: Login com Google via Credential Manager, Firebase App Check (Play Integrity), Crashlytics, Remote Config e tema claro/escuro, com targetSdk 36.

### 🕒 [JornadaCerta](https://github.com/LucasPaivac/JornadaCerta)
Assistente preventivo de controle de jornada com notificações inteligentes e persistência offline.
 - Sistema de Notificações Ativo: Implementação avançada de AlarmManager e BroadcastReceiver para agendamento de lembretes em background, garantindo pontualidade mesmo com o app encerrado.
 - Arquitetura & Clean Code: Estrutura baseada em MVVM e Clean Architecture, utilizando Hilt para uma injeção de dependências modular com escopos de Singleton e ViewModel.
 - Persistência Robusta: Gerenciamento de histórico de registros com Room Database, garantindo integridade de dados e suporte a operações assíncronas com Kotlin Coroutines.
 - UX com Validação Dinâmica: Interface reativa em Jetpack Compose (Material 3) com validação de regras de negócio em tempo real para evitar registros de saída antecipada.
 - Modern Android Standards: Tratamento completo de permissões para Android 12+ (SCHEDULE_EXACT_ALARM) e Android 13+ (POST_NOTIFICATIONS), com suporte nativo a Dark & Light Mode.

### 🎬 [CineApp](https://github.com/LucasPaivac/CineApp)
Exploração de catálogo de filmes utilizando a API do TMDB Highlights:
- Dependency Injection: Implementação completa com Hilt, utilizando @Module, @Provides e @Binds para um grafo de dependências desacoplado.
- Arquitetura & Clean Code: Implementação rigorosa de MVVM, Clean Architecture e Mappers para separação de responsabilidades.
- Otimização de Performance: Uso de append_to_response para reduzir o consumo de rede e Lazy Layouts para fluidez de scroll.
- UI Imersiva: Design moderno com Jetpack Compose, utilizando gradientes dinâmicos e alinhamentos de imagem avançados.
- Qualidade de Software: Cobertura de lógica de negócio com Unit Tests utilizando Turbine, MockK e objetos Fake.

### 🍲 [EasyRecipes](https://github.com/LucasPaivac/EasyRecipes)
*Assistente de cozinha moderno usando a API Spoonacular* **Highlights:** - Arquitetura robusta com **MVVM** e **Clean Architecture**.
- IU reativa com **Jetpack Compose** e **StateFlow**.
- Base de código confiável com **Unit Tests** (Turbine, Flow & Mockito).
- Abordagem offline-first (se aplicável).

## 📫 Contact
- [LinkedIn](https://www.linkedin.com/in/lucas-paiva-cedro-149452122/) 
- Email: paivacedrodev@gmail.com
