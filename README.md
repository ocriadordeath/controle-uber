# Controle Uber — Android

Projeto inicial nativo Android em Kotlin + Jetpack Compose.

## O que já funciona
- Cadastro manual de ganhos, combustível e outras despesas.
- Cálculo automático de ganhos, despesas, combustível e lucro líquido.
- Histórico de lançamentos com opção de excluir.
- Dados salvos localmente no aparelho (SharedPreferences/JSON).
- Interface escura e adaptada para celular.

## Como gerar o APK
1. Instale o Android Studio em um computador.
2. Abra a pasta `ControleUberAndroid` no Android Studio.
3. Aguarde a sincronização do Gradle.
4. Selecione **Build > Build Bundle(s) / APK(s) > Build APK(s)**.
5. O APK de depuração será gerado em `app/build/outputs/apk/debug/`.

## Observações
- Este projeto é uma primeira versão e não se conecta à Uber.
- Os valores são inseridos manualmente.
- O lucro calculado considera somente os lançamentos cadastrados.
- Próximas melhorias recomendadas: filtros por dia/semana/mês, km rodados, horas trabalhadas, metas e exportação CSV.
