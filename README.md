🚗 FuelWise

FuelWise é um aplicativo desenvolvido em Flutter que tem como objetivo ajudar o usuário a decidir se compensa abastecer com gasolina ou etanol, com base nos preços informados e na regra de rendimento entre os combustíveis.

O projeto está sendo desenvolvido de forma incremental, com foco em organização, clareza de código e boa experiência do usuário.
_________________________________________________________________________________________________________________________________
🎯 Objetivo do Projeto

O FuelWise permite que o usuário:

Informe o preço da gasolina

Informe o preço do etanol

Visualize qual combustível compensa mais

Entenda como o cálculo é feito, através de um card explicativo no app

A decisão é baseada na regra dos 70%, amplamente utilizada no Brasil:

O etanol compensa quando seu preço é até 70% do valor da gasolina.
_________________________________________________________________________________________________________________________________

🛠️ Tecnologias Utilizadas

Flutter – desenvolvimento multiplataforma

Dart – linguagem principal

Cubit – gerenciamento de estado (flutter_bloc)

Arquitetura modular por responsabilidade

UI customizada com componentes reutilizáveis.

_________________________________________________________________________________________________________________________________

🧠 Gerenciamento de Estado

O gerenciamento de estado é feito utilizando Cubit, garantindo:

Separação clara entre lógica e interface.

Código mais previsível e fácil de manter.

Melhor controle sobre estados de cálculo e resultado.

_________________________________________________________________________________________________________________________________

📂 Estrutura de Pastas

```
lib/
├── cubit/
│   ├── fuel_cubit.dart
│   └── fuel_state.dart
│   (responsável pelo gerenciamento de estado da aplicação utilizando Cubit)
│
├── domain/
│   ├── entities/
│   │   └── fuel_result.dart
│   │      (entidade que representa o resultado do cálculo entre os combustíveis)
│   │
│   └── service/
│       └── fuel_service.dart
│          (contém a regra de negócio responsável por calcular se compensa gasolina ou etanol)
│
├── src/
│   └── home_page.dart
│      (tela principal do aplicativo onde o usuário informa os preços)
│
├── utils/
│   ├── app_assets.dart
│   ├── app_colors.dart
│   ├── app_sizes.dart
│   └── app_text_style.dart
│      (arquivos responsáveis por centralizar constantes visuais e padronização de estilos)
│
├── widgets/
│   ├── card_info.dart
│   ├── footer.dart
│   ├── forms.dart
│   ├── header.dart
│   └── result_dialog.dart
│      (componentes reutilizáveis da interface do usuário)
│
└── main.dart
   (ponto de entrada da aplicação)
```
_________________________________________________________________________________________________________________________________

🚀 Status do Projeto

🔧 Em desenvolvimento
📈 Evoluindo passo a passo
📢 Progresso sendo documentado no LinkedIn

📌 Próximos Passos (planejado)

Melhorias de UX.

Refatorações e organização adicional da arquitetura.

_________________________________________________________________________________________________________________________________

👤 Autor

Desenvolvido por Lucas Batista.

💻 GitHub: https://github.com/LucasBatistaX

💼 LinkedIn: https://github.com/LucasBatistaX
