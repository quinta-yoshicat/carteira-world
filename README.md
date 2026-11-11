# carteira-world

Página **pessoal e não oficial** para o dono usar o seu próprio Safe (`0xd047…d2B1`, World Chain e Optimism) com a chave do dono, fora de qualquer app oficial.

**Não é um produto da World nem da Worldcoin.** Não é oferecida a outros utilizadores. O endereço do Safe está fixo no código porque a página serve uma única pessoa.

## O que faz (estado atual)
- Mostra o saldo e os tokens do Safe.
- Envia tokens do Safe (um a um ou em lote por MultiSend).
- Troca tokens (swap) com cotação da LI.FI e verificação do preço de mercado. A única aprovação criada é do Safe para o contrato de troca devolvido pela cotação, pelo valor exato dessa troca.
- Cada operação é assinada pela MetaMask do dono. A chave privada nunca entra na página.

## Ainda não existe
- Ponte entre redes (botão marcado como "em breve").
