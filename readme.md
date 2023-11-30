Projeto de Mapeamento e Análise de Morcegos na Mata Atlântica
Se você é estudante de MBA e está procurando uma solução para esta atividade, este projeto pode ser útil para você.

Construção do Mapa
Construa um mapa que represente a Mata Atlântica inserida no território brasileiro.

Adicione pontos de registros de espécies de morcegos no mapa.

Classifique os pontos por status de conservação.

Classifique os pontos pela abundância controlada pelo esforço amostral.

Arrume as legendas com a escrita correta.

Utilize o comando a seguir para salvar o gráfico em resolução de 600dpi e formato TIFF no diretório:

ggsave('mapa_mata_atlantica_morcegos.tif', dpi = 600, device = 'tiff')
Criação de Gráficos
Crie um gráfico de pontos plotando nos eixos o esforço amostral e a abundância. Após a criação do gráfico, explique se você utilizou o comando a seguir e por quê:


dados <- rename(dados, EA = "esforco amostral")
Este comando renomeia a coluna "esforco amostral" para "EA" no conjunto de dados "dados".

Crie um gráfico boxplot da abundância controlada pelo esforço amostral apenas para espécies da família Phyllostomidae.

Ajuste o ângulo das etiquetas das espécies no gráfico para evitar sobreposição.

Salve o gráfico em formato JPEG com resolução de 300dpi. Certifique-se de que a largura do gráfico não cause sobreposição nos nomes das espécies.

Criação de Grid de Gráficos
Crie um grid de gráficos de pontos de esforço amostral por abundância, organizando as famílias nas colunas e os status de conservação nas linhas.

Atribua cores diferentes ao fundo dos títulos das colunas e das linhas.

Salve o grid de gráficos em formato PDF com resolução de 600dpi no diretório.

Manipulação do Banco de Dados
Crie uma nova coluna chamada "media_ocorrencia" com a média da abundância por espécie.

Salve esta planilha com a nova coluna no diretório.

Para obter mais informações ou suporte, entre em contato pelo e-mail: tmarketing220@gmail.com. Contatos devem ser feitos exclusivamente por esse meio.