# GxClipboard
Copia um texto para o Clipboard (Web)

## Instalação

Genexus 16 ou Superior:

```sh
1 - Na IDE Genexus, navegue em Knowledge Manager / Import.
2 - Selecione o Arquivo UCGxClipboard.xml ** Note que é preciso alterar o filtro da caixa de seleção para XML.
```

## Exemplo de uso
```Gx
Event 'DoCopiarLink'

	UCClipboard.SetClipBoard(&SuaVariavel)
	
EndEvent	
```
