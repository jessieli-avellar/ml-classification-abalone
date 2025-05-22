# :shell: Abalone - A comparison of Machine Learning binary classification models in Python
[![Badge](https://img.shields.io/badge/lang-EN-blue)](#-english) [![Badge](https://img.shields.io/badge/lang-PT--BR-green)](#-português)

---

<details>
<summary id="english-doc"> Click here to read the documentation in 🇺🇸 <strong>English </strong></summary>
  <br>
  
  ---
  :white_check_mark: **RESULTS:** 
  <b>81.91% accuracy</b>  rate in identifying mature abalone when applying the SVC model with all the information available.
  <br>
  
  ### Business comprehension
  
  [*Abalone*](https://en.wikipedia.org/wiki/Abalone) is a common name for marine gastropod molluscs in the family *Haliotidae*. The inner layer of the shell in many species is highly iridescent which make the shells attractive to humans as ornaments, jewelry, and as a source of colorful mother-of-pearl.
  
  <table>
    <tr>
      <td><img src="https://i0.wp.com/geologyscience.com/wp-content/uploads/2024/11/Abalone-Shell.jpg?fit=2560%2C1769&ssl=1" width="300"/></td>
      <td><img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcT0RUnyxT9eD6FWVSkPdTjNGxvtzRtkpcuUyQ&s" width="250"/></td>
    </tr>
    <tr>
      <td align="center">Example of Abalone</td>
      <td align="center">Object made with abalone shell</td>
    </tr>
  </table>
  
  In 2022 the [International Union for Conservation of Nature (IUCN)](https://iucn.org/press-release/202212/human-activity-devastating-marine-species-mammals-corals-iucn-red-list) carried out the first global assessment of abalone species, revealing that **20 of the 54 known species are threatened with extinction**. Overfishing, both legal and illegal, is a determining factor in the decline of abalone populations worldwide.
  
  In this analysis, the assumption was made that the correct identification of whether an abalone was young (<= 9 rings) or mature (> 9 rings) would be essential for the business in question, and that only the capture of mature abalones was desired. Incorrectly catching young abalone could negatively affect the yield of caputura in a later year, due to a decrease in the population in the area.
  
  ```mermaid
  graph TD
    S@{ shape: sm-circ, label: "Small start" } --> A@{ shape: diamond, label: "Does abalone have **more than 9** rings?" }
    A --> B["**SIM**: **Mature** abalone"]
    A --> C["**NÃO**: **Young** abalone"]
    B --> t@{ shape: framed-circle, label: "Stop" }
    C --> t@{ shape: framed-circle, label: "Stop" }
  ```
  
  ### About the Dataset
  The dataset used was ["Abalone Data Set"](https://archive.ics.uci.edu/ml/datasets/abalone). This data was originally obtained from the scientific article:
  > Warwick J Nash, Tracy L Sellers, Simon R Talbot, Andrew J Cawthorn and Wes B Ford (1994)
  **"The Population Biology of Abalone (_Haliotis_ species) in Tasmania. I. Blacklip Abalone (_H. rubra_) from the North Coast and Islands of Bass Strait"**,
  Sea Fisheries Division, Technical Report No. 48 (ISSN 1034-3288)
  <br>
  <br>

</details>




<details>
<summary id="portuguese-doc">Clique aqui para ler a documentação em 🇧🇷 <strong>Português </strong></summary>

  <br>

  ---
  
  :white_check_mark: **RESULTADO:** 
  Obtido <b>81.91% de acerto</b>  entre os abalones identificados como maduros ao aplicar o modelo SVC com todas as informações disponíveis.
  <br>
  
  ### Entendendo o problema
  
  [*Abalone*](https://pt.wikipedia.org/wiki/Abalone) é um nome comum para moluscos gastrópodes marinhos da família *Haliotidae*. A camada interna da concha em muitas espécies é altamente iridescente, o que torna as conchas atraentes para os seres humanos como ornamentos, jóias e como fonte de madrepérola colorida.
  
  <table>
    <tr>
      <td><img src="https://i0.wp.com/geologyscience.com/wp-content/uploads/2024/11/Abalone-Shell.jpg?fit=2560%2C1769&ssl=1" width="300"/></td>
      <td><img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcT0RUnyxT9eD6FWVSkPdTjNGxvtzRtkpcuUyQ&s" width="250"/></td>
    </tr>
    <tr>
      <td align="center">Examplo de Abalone</td>
      <td align="center">Objeto feito com concha de abalone</td>
    </tr>
  </table>
  
  Em 2022 a [União Internacional para a Conservação da Natureza (IUCN)](https://iucn.org/press-release/202212/human-activity-devastating-marine-species-mammals-corals-iucn-red-list) realizou a primeira avaliação global das espécies de abalone, revelando que **20 das 54 espécies conhecidas estão ameaçadas de extinção**. A pesca excessiva, tanto legal quanto ilegal, é um fator determinante no declínio das populações de abalone em todo o mundo.
  
  Nessa análise, foi feita a suposição de que a correta identificação entre um abalone jovem (<= 9 anéis) ou maduro (> 9 anéis) seria essencial para o negócio em questão, sendo desejada apenas a captura dos abalones maduros. Uma incorreta captura de abalones jovens poderia afetar negativamente o rendimento das caputura em um ano posterior, devido a uma diminuição da população na área.
  
  ```mermaid
  graph TD
    S@{ shape: sm-circ, label: "Small start" } --> A@{ shape: diamond, label: "O abalone possui **mais de 9** anéis?" }
    A --> B["**SIM**: Abalone **maduro**"]
    A --> C["**NÃO**: Abalone **jovem**"]
    B --> t@{ shape: framed-circle, label: "Stop" }
    C --> t@{ shape: framed-circle, label: "Stop" }
  ```
  
  ### Sobre os Dados
  O dataset utilizado foi ["Abalone Data Set"](https://archive.ics.uci.edu/ml/datasets/abalone). Esses dados foram originalmente obtidos do artigo científico:
  > Warwick J Nash, Tracy L Sellers, Simon R Talbot, Andrew J Cawthorn and Wes B Ford (1994)
  **"The Population Biology of Abalone (_Haliotis_ species) in Tasmania. I. Blacklip Abalone (_H. rubra_) from the North Coast and Islands of Bass Strait"**,
  Sea Fisheries Division, Technical Report No. 48 (ISSN 1034-3288)
</details>
