# Orbit Play

Clientes independentes de Remote Play para Windows x64 e Android, com identidade visual própria.

Orbit Play não é desenvolvido, afiliado, aprovado ou certificado pela Sony Interactive Entertainment. PlayStation, PS4, PS5 e DualSense são marcas de seus respectivos titulares.

## Downloads oficiais

- **Android:** distribuição oficial exclusivamente pelo [Google Play](https://play.google.com/store/apps/details?id=com.marlontimbo.orbitplay), inclusive para testadores. Para participar do teste fechado Alpha, use uma conta convidada e o [link oficial de adesão](https://play.google.com/apps/testing/com.marlontimbo.orbitplay). A disponibilidade depende da faixa de testes e da autorização da conta.
- **Windows:** instalador x64 ou pacote portable nas [Releases deste repositório](https://github.com/azztroMT/OrbitPlay/releases).
- **Código-fonte correspondente:** arquivos `OrbitPlay-Windows-<versão>-source.zip` e `OrbitPlay-Android-<versão>-source.zip` anexados a cada release, contendo instruções de build e licenças. Os arquivos automáticos “Source code” do GitHub correspondem apenas ao conteúdo deste repositório de distribuição.

## Versão 0.4.1

Atualizador integrado, verificação manual, changelog, progresso real e validação de origem, manifesto assinado, hash, tamanho e identidade dos pacotes. Mantidos os recursos da 0.4.0, incluindo perfis por console, overlay e multiplayer Windows.

**Histórico Android:** a 0.4.1 inaugurou a assinatura permanente. Os APKs e AABs históricos deixaram de ser oferecidos publicamente neste repositório; a distribuição oficial Android e suas atualizações passam exclusivamente pelo Google Play. Não desinstale a versão Play nem limpe seus dados para migrar para um APK. Nenhuma chave privada é publicada aqui.

## Atualizações e segurança

Android recebe as atualizações oficiais pelo Google Play. Compras, licença vitalícia e restauração permanecem no fluxo Google Play existente.

O atualizador **Windows** mantém a origem oficial fixa `azztroMT/OrbitPlay`, as releases públicas, `orbit-update.json`, `orbit-update.sig` e o instalador Windows. O manifesto assinado, o hash, o tamanho e a identidade do pacote são verificados antes de abrir o instalador. Não há atualização silenciosa. As referências Android nos manifestos históricos são preservadas para manter os bytes e assinaturas originais.

As limitações e os testes estão documentados no relatório de cada release. Multiplayer e atualização sobre instalações reais precisam ser validados no hardware correspondente; testes automatizados não substituem essa validação.

## Licenças

A distribuição inclui componentes AGPL e outras dependências open source. A exclusividade do canal oficial Android não restringe os direitos de uso, modificação e redistribuição concedidos por essas licenças. Os arquivos-fonte correspondentes e os avisos de cada componente acompanham as releases. Consulte `LICENSE` e os arquivos de licença de cada pacote-fonte antes de redistribuir ou modificar.
