# Orbit Play

Clientes independentes de Remote Play para Windows x64 e Android, com identidade visual própria.

Orbit Play não é desenvolvido, afiliado, aprovado ou certificado pela Sony Interactive Entertainment. PlayStation, PS4, PS5 e DualSense são marcas de seus respectivos titulares.

## Downloads oficiais

Use somente as [Releases deste repositório](https://github.com/azztroMT/OrbitPlay/releases).

- **Windows:** instalador x64 ou pacote portable.
- **Android:** APK para instalação direta. O AAB é disponibilizado como artefato de distribuição; não é um instalador de uso direto.
- **Código-fonte correspondente:** arquivos `OrbitPlay-Windows-<versão>-source.zip` e `OrbitPlay-Android-<versão>-source.zip` anexados a cada release, contendo instruções de build e licenças. Os arquivos automáticos “Source code” do GitHub correspondem apenas ao conteúdo deste repositório de distribuição.

## Versão 0.4.1

Atualizador integrado, verificação manual, changelog, progresso real e validação de origem, manifesto assinado, hash, tamanho e identidade dos pacotes. Mantidos os recursos da 0.4.0, incluindo perfis por console, overlay e multiplayer Windows.

**Android:** a 0.4.1 inaugura a assinatura permanente da distribuição direta. A troca da assinatura anterior impede atualização por cima da instalação antiga: preserve os dados necessários antes de desinstalá-la e instale o novo APK manualmente. As versões posteriores usarão a mesma chave. Nenhuma chave privada é publicada aqui.

## Atualizações e segurança

Origem oficial fixa: `azztroMT/OrbitPlay`. Atualizações são iniciadas pelo usuário e dependem de releases completas contendo `orbit-update.json`, `orbit-update.sig` e o pacote da plataforma. O manifesto é assinado e os downloads são verificados antes de abrir o instalador. Não há atualização silenciosa.

As limitações e os testes estão documentados no relatório de cada release. Multiplayer e atualização sobre instalações reais precisam ser validados no hardware correspondente; testes automatizados não substituem essa validação.

## Licenças

A distribuição inclui componentes AGPL e outras dependências open source. Os arquivos-fonte correspondentes e os avisos de cada componente acompanham as releases. Consulte `LICENSE` e os arquivos de licença de cada pacote-fonte antes de redistribuir ou modificar.
