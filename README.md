# Android Studio Utils 

Este repositório tem como o objetivo abrigar uma série de utilidades para o desenvolvimento no Android Studio, inicialmente o foco será em Live Templates e possivelmente evoluirá para plugins que possam ser considerados utéis de alguma forma.


### Conteúdo
#### Live Templates

Para criar um live template no Android Studio, siga os seguintes passos.

`Android Studio → Preferences → Editor → Live Templates`

Se tudo ocorreu corretamente, você está nessa tela :

<img src="Images\Editor.PNG" alt="Editor" style="zoom:80%;" />



Uma vez aqui, você deve selecionar qual categoria se encaixa o live template que você deseja criar, neste caso é AndroidKotlin.

Logo após, dê um click no + localizado no canto superior direito e selecione a opção de Live Template, chegando nesta tela abaixo.



<img src="Images\Fields.PNG" alt="Fields" style="zoom:75%;" />



Aqui você deve preencher os campos:

- Abbreviation : atalho a ser utilizado para que o template seja criado.
- Description :  descrição sobre ao que se refere o template que está sendo inserido.
- Template Text : o template a ser inserido
- Context : o context no qual o seu template pode ser inserido, sendo definido no dropdown logo ao lado do warning.

Uma vez preenchido os campos, resta apenas dar o apply e ser feliz.

Para a utilização do live template é necessário apenas que você digite a abreviação que foi colocada na hora de criar e apertar Ctrl + espaço.

### File Templates

A ideia dos file templates é similar aos live templates, a sua criação segue o mesmo primeiro passo porém você deve acessar 

`Android Studio → Preferences → Editor → File and Code Templates`

Uma vez seguindo esses passos você se encontrará nesta tela.

<img src="Images\FileTemplates.PNG" alt="FileTemplates" style="zoom:75%;" />



Click no + localizado no canto superior esquerdo e preencha os campos :

- Name : Nome do file template
- Extension  : Extensão do live template (neste caso kt, por se tratar de Kotlin)

Uma vez preenchidos, click no apply e seja feliz.

Para a utilização do file template,  você deve criar um arquivo e selecionar o template que foi criado.



#### Templates a serem abordados

##### File Templates

- [x] Activity (onCreate)[Com Databinding]

- [x] Fragment (onCreateView)[Sem Databinding]

##### Live Templates

- Databinding Utils
  - [x] Activity 
  - [x] Fragment
- Lists

  - [ ] RecyclerView XML
  - [ ] Adapter

- XML
  - [x] Component constraints
