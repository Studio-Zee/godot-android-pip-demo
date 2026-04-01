DisplayServer.pip_mode_set_auto_enter_on_background(true) ativa automaticamente o modo Picture-in-Picture (PiP) no Android quando o usuário sai do aplicativo (por exemplo, ao pressionar o botão Home). Com isso, o jogo continua rodando em uma pequena janela no canto da tela, semelhante ao que acontece com vídeos no YouTube.

Esse recurso é útil principalmente para jogos que não exigem interação constante, como idle games ou durante cutscenes.

Caso queira testar, pode usar no _ready() que seria mais rápido ou _process() com um botão...

```gdscript
DisplayServer.pip_mode_set_auto_enter_on_background(true)
```

Demonstração baseada no projeto oficial da Godot:

https://github.com/godotengine/godot/pull/114505
