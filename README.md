# Dice_Roller_App
Esse é um app para trabalhar os conceitos de ViewGoup e Activity.

![Image](https://github.com/luishads/Dice_Roller_App/blob/master/DiceRoller_V1_02.png)

# ViewGoup
Um **ViewGroup** é um `View`— muitas vezes invisível para o usuário — que contém e posiciona outras visualizações dentro dele (chamadas de seus filhos), criando uma **hierarquia de visualização** . Qualquer layout para um aplicativo Android sempre começa com a `ViewGroup`como pai e contém visualizações filhas.

Quando existem `Views` em um `ViewGroup`, as `Views` são consideradas *filhas* do `ViewGroup` *pai*. No caso desse app, o `ImageView` e o `Button` são considerados filhos do `ConstraintLayout` pai.

Quando falamos em `ViewGroup` e `ConstraintLayout` estamos nos referindo a parte de layout do app, mais precisamente no arquivo [activity_main.xml](https://github.com/luishads/Dice_Roller_App/blob/master/app/src/main/res/layout/activity_main.xml). Nele nossa UI é construida.

# Activity

Uma `Activity` disponibiliza a janela em que o app desenha a IU. Normalmente, uma `Activity` ocupa toda a tela do app em execução. Cada app tem uma ou mais atividades. A primeira atividade ou de nível superior costuma ser chamada de `MainActivity` e é disponibilizada pelo modelo de projeto. Por exemplo, quando o usuário rola a lista de apps no dispositivo e toca no ícone de um app, o sistema Android inicia a `MainActivity` do app.

No código `MainActivity`, é necessário fornecer detalhes sobre o layout da `Activity` e como o usuário deve interagir com ele.

Para apps mais complicados, pode haver várias telas e mais de uma `Activity`. Cada `Activity` tem uma finalidade específica. Por exemplo, em um app de galeria de fotos, você pode ter uma `Activity` para exibir uma grade de fotos, uma segunda `Activity` para visualizar somente uma foto e uma terceira `Activity` para editar uma foto específica.

No app em questão, nossa `MainActivity` contem o código com as instruções para rolagem dos dados quando o botão é clicado. [MainActivity.kt](https://github.com/luishads/Dice_Roller_App/blob/master/app/src/main/java/com/example/diceroller/MainActivity.kt)

## Referência:
[Google codelab DiceRoller](https://developer.android.com/courses/pathways/android-basics-kotlin-four)
