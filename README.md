# Guia de execução e teste do artefato

Este repositório disponibiliza o artefato desenvolvido para o Trabalho de Conclusão de Curso (TCC). Este guia apresenta os procedimentos necessários para preparar o ambiente, executar o programa e realizar testes básicos de funcionamento.

## 1. Sobre o artefato

O artefato é disponibilizado no arquivo `Artefato_TCC.zip`. Após a extração, são encontrados os seguintes arquivos:

- `Projeto TCC_LTS_MELHOR.exe` — executável do programa.
- `data.win` — arquivo de dados utilizado pelo programa.
- `musicas.dat` — dados de áudio/músicas.
- `efeitos_sonoros.dat` — dados de efeitos sonoros.
- `options.ini` — arquivo de configuração.

**Importante:** mantenha todos esses arquivos na mesma pasta. O executável depende dos arquivos de dados para funcionar corretamente.

## 2. Requisitos para execução

Antes de iniciar, verifique se o ambiente atende aos seguintes requisitos:

- Computador com sistema operacional Windows.
- Permissão para extrair arquivos ZIP e executar programas.
- DirectX 11 compatível com o sistema e com o dispositivo gráfico.

O executável foi identificado como uma aplicação Windows que utiliza a API gráfica DirectX 11. Não é necessário instalar ferramentas de desenvolvimento para realizar o teste do artefato.

## 3. Preparação do ambiente

1. Faça o download ou clone deste repositório para o computador.
2. Localize o arquivo `Artefato_TCC.zip`.
3. Extraia o conteúdo do ZIP para uma pasta de sua preferência. Por exemplo: `C:\TCC\Artefato`.
4. Abra a pasta extraída e confirme que o executável e os quatro arquivos auxiliares estão juntos.
5. Não execute o programa diretamente de dentro do arquivo ZIP.

> Caso o repositório tenha sido baixado pela opção **Code > Download ZIP** do GitHub, extraia primeiro o ZIP do repositório. Em seguida, extraia também o arquivo `Artefato_TCC.zip` que está dentro dele.

## 4. Como executar o artefato

1. Abra a pasta na qual os arquivos do artefato foram extraídos.
2. Dê dois cliques em `Projeto TCC_LTS_MELHOR.exe`.
3. Aguarde o carregamento do programa.
4. Utilize as opções e funcionalidades apresentadas na interface para realizar a avaliação.

Se o Windows exibir uma janela de confirmação de segurança, verifique se o arquivo foi obtido deste repositório e siga as políticas de segurança da instituição ou do computador utilizado. Não desative o antivírus ou outras proteções do sistema para executar o artefato.

## 5. Roteiro de teste

Execute os passos abaixo para verificar o funcionamento geral do artefato. Registre o resultado de cada etapa.

| Etapa | Procedimento | Resultado esperado |
|---|---|---|
| 1. Inicialização | Abrir `Projeto TCC_LTS_MELHOR.exe`. | O programa inicia sem apresentar erro ou encerrar inesperadamente. |
| 2. Carregamento | Aguardar a abertura completa. | A interface/tela inicial é apresentada corretamente. |
| 3. Navegação | Interagir com as opções disponíveis na interface. | Os comandos respondem às interações e as telas/estados correspondentes são apresentados. |
| 4. Recursos de áudio | Verificar, durante o uso, os recursos de música e efeitos sonoros disponibilizados. | Os áudios previstos para as ações são reproduzidos, quando aplicável. |
| 5. Encerramento | Utilizar a opção de saída do programa ou fechá-lo normalmente. | O programa é encerrado sem travamento. |

O roteiro acima é uma verificação funcional básica. Para uma avaliação completa, execute também os cenários e critérios de teste definidos no trabalho acadêmico.

## 6. Registro dos resultados

Durante os testes, recomenda-se registrar:

- Sistema operacional e versão utilizados.
- Se o programa iniciou corretamente.
- Quais funcionalidades foram testadas.
- Resultado observado em cada etapa do roteiro.
- Mensagens de erro, falhas visuais ou comportamentos inesperados.
- Evidências, como capturas de tela, quando pertinente.

Ao identificar um problema, informe os passos realizados imediatamente antes da ocorrência e, se possível, inclua uma captura de tela e a mensagem de erro.

## 7. Solução de problemas

**O programa não inicia**

- Confirme que o ZIP interno foi extraído por completo.
- Verifique se `data.win`, `musicas.dat`, `efeitos_sonoros.dat` e `options.ini` estão na mesma pasta do executável.
- Tente executar o programa em uma versão compatível do Windows com suporte ao DirectX 11.
- Verifique se o sistema está atualizado e se os drivers gráficos estão funcionando corretamente.

**O programa abre, mas apresenta falhas de áudio**

- Verifique o volume do sistema e a saída de áudio selecionada.
- Confirme que `musicas.dat` e `efeitos_sonoros.dat` permanecem na pasta do executável.

**O programa apresenta erro ou fecha inesperadamente**

- Registre a mensagem apresentada.
- Anote a etapa em que o problema ocorreu.
- Repita o teste após confirmar que todos os arquivos foram extraídos corretamente.

## 8. Estrutura dos arquivos

```text
TCC_Download/
├── README.md
└── Artefato_TCC.zip
    ├── Projeto TCC_LTS_MELHOR.exe
    ├── data.win
    ├── musicas.dat
    ├── efeitos_sonoros.dat
    └── options.ini
```

## 9. Observações

- Não renomeie nem remova os arquivos que acompanham o executável.
- Mantenha os arquivos do artefato na mesma pasta.
- Este repositório disponibiliza uma versão compilada para execução no Windows; o código-fonte do projeto não está incluído no pacote do artefato.
- Caso sejam disponibilizadas novas versões, utilize os arquivos da mesma versão em conjunto.

---
**Artefato desenvolvido como parte de um Trabalho de Conclusão de Curso (TCC).**
