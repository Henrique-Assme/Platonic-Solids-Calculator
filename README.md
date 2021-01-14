# Platonic-Solids-Calculator
This programm is a calculator for faces, vertices, edges, area and volume for the five platonic solids, known as tetrahedron, hexahedron, octahedron, dodecahedron and icosahedron.

# Criando o programa
Para a interface do programa utilizei 10 textViews, 8 EditText e 2 botões, ficando desta maneira:

![1](https://user-images.githubusercontent.com/69920692/104632604-b787dd00-567c-11eb-8a90-c1f677fd659f.PNG)

Na parte dos cógidos primeiro declarei todos os campos que iria utilizar:

![2](https://user-images.githubusercontent.com/69920692/104632795-fc137880-567c-11eb-9c04-05d34ce57d9f.PNG)

Depois disso, foi feito o método OnClick do botão calcular. Primeiro é feita uma verificação se os campos não estão vazios. Se tudo estiver certo, as variáveis lado e n recebem seus valores e são enviadas para o método "dados", onde os cálculo serão feitos.

Existe uma verificação com essa variável "a" que certifica de que os números colocados para "lado" pertencem ao intervalo {4,6,8,12,20}. Qualquer outro valor para "lado" colocado resulta numa mensagem dizendo que não foi possível realizar os cálculos.
Se o "a" não tiver seu valor alterado (a = 0), então o programa exibe na tela os resultados obtidos pelo método "dados".

![3](https://user-images.githubusercontent.com/69920692/104633508-01bd8e00-567e-11eb-9919-b3d7d59d34b6.PNG)

E aqui é o método "dados", com um if para cada um dos sólidos e suas respectivas fórmulas e resultados.

![4](https://user-images.githubusercontent.com/69920692/104633509-02562480-567e-11eb-8fc4-fa9446561dfe.PNG)

![5](https://user-images.githubusercontent.com/69920692/104633510-02eebb00-567e-11eb-845f-8626984ee5b8.PNG)

Também existe o botão "Limpar" que simplesmente limpa todos os campos para o usuário.

![6](https://user-images.githubusercontent.com/69920692/104633512-02eebb00-567e-11eb-9367-efad7bb0d7e4.PNG)

Está pronto o programa!!
