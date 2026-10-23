# A.T.L.A.S.

O app de voz da Casa (fala-se "Atlas"): uma página só (GitHub Pages) que escuta, fala e conversa. O cérebro mora no App Carteira
(`src/Voz.js`, implantação "voz"); aqui não há dado nenhum nem chave: a chave pessoal é digitada no iPhone e fica só nele.

Como funciona: toque no círculo e converse. Ele cumprimenta, ouve, responde falando e volta a ouvir sozinho até
"tchau". No computador (Chrome) o navegador reconhece a voz; no iPhone a página grava e a Carteira transcreve
(Whisper, na Groq). No computador, você pode começar a falar por cima para interromper uma resposta. No iPhone,
toque no círculo enquanto ele fala e diga o próximo pedido imediatamente. Na primeira vez, cole o "link da siri"
(da caixa de comando da Casa).
