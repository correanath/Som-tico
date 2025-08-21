# 🧬 Pipeline Somático

Este repositório contém o notebook **Pipeline_Somatico.ipynb**, desenvolvido no Google Colab para análise somática.

## 🚀 Como executar o notebook

### Clique no link abaixo para abrir diretamente no Google Colab:

- [Abrir Pipeline_Somatico.ipynb no Colab](https://colab.research.google.com/drive/15Uax-INdQc2A_MaLWOtYsx0zxpxi0YrH?usp=sharing)


Escopo: As neoplasias mieloproliferativas (NMPs) negativas para o cromossomo Filadélfia, que incluem policitemia vera (PV), trombocitemia essencial (ET) e mielofibrose primária (PMF), são doenças adquiridas de células-tronco hematopoéticas clonais caracterizadas pela proliferação anormal e acúmulo de células sanguíneas maduras . A mielofibrose é caracterizada pela desregulação do estroma da medula óssea com o desenvolvimento de uma fibrose de reticulina. Entre as NMPs, a mielofibrose está associada ao pior prognóstico, e sua evolução é extremamente variável de acordo com as características prognósticas e tratamento. As terapias adaptadas ao risco variam desde nenhum tratamento até o transplante alogênico de células-tronco hematopoéticas. Mais de 90% dos casos de mielofibrose abrigam mutações somáticas nos genes controladores JAK2 , CALR ou MPL que levam a uma ativação constitutiva da via JAK-STAT5. Outras mutações somáticas não-condutor (as chamadas mutações adicionais) têm sido cada vez mais detectadas no MPN com o uso de sequenciamento de alto rendimento. Essas mutações adicionais envolvem genes com várias funções, como epigenética, splicing, sinalização e fatores de transcrição, e também são mutados em outras neoplasias mieloides, como síndromes mielodisplásicas e LMA.

Objetivo geral: análise de variantes somáticas detectadas em genes de alto risco que são fatores prognósticos adversos na Mielofibrose (MF).

Requisitos mínimos do trabalho:

Rodar um pipeline somático e anotação das variantes somáticas.
Identificação de amostras com alterações de TP53 e genes de alto risco ( EZH2, CBL, U2AF1, SRSF2, IDH1, IDH2, NRAS ou KRAS ) que são fatores prognósticos adversos na mielofibrose.
Da coorte de 30 indivíduos selecionados para a atividade, 28 apresentaram variantes nos genes de interesse (TP53, EZH2, CBL, U2AF1, SRSF2, IDH1, IDH2, NRAS, KRAS). Além dos genes citados como fatores prognósticos adversos na mielofibrose e maiores risco de transformação leucêmica, também encontramos variantes em outros genes, porém nem todos relacionados à PMF. A grande maioria dos indivíduos possuem variantes no gene CBL. Este gene é um proto-oncogene que codifica uma ubiquitina ligase RING finger E3. A proteína codificada é uma das enzimas necessárias para direcionar substratos para degradação pelo proteassoma. Esta proteína medeia a transferência de ubiquitina das enzimas de conjugação de ubiquitina (E2) para substratos específicos. Além disso, contém um domínio de ligação de fosfotirosina N-terminal que lhe permite interagir com vários substratos fosforilados em tirosina e direcioná-los para a degradação do proteassoma. Como tal, funciona como um regulador negativo de muitas vias de transdução de sinal. A mutação nesse gene está presente em diversos tipos de câncer, incluindo leucemia mielóide aguda, e a expansão de repetições CGG no 5' UTR foi associada à síndrome de Jacobsen. No caso de pacientes que possuem PMF, estudos demonstram OS reduzida. As mutações nos demais genes aparecem em menor frequência, porém sabe-se que esses genes estão associados à diversos tipos de câncer. Segue o pipeline utilizado para anotação e realização das análises. 
