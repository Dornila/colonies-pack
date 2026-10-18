# Colonies

Сборка Minecraft 1.21.1 (NeoForge) для нашего сервера. Обновляется сама при запуске игры через packwiz.

Prism → Изменить → Параметры → Пользовательские команды → Предстартовая команда
(`packwiz-installer-bootstrap.jar` лежит в папке `minecraft` экземпляра):

ПК:
```
"$INST_JAVA" -jar "$INST_MC_DIR/packwiz-installer-bootstrap.jar" --bootstrap-main-jar "$INST_MC_DIR/packwiz-installer.jar" -s client --pack-folder "$INST_MC_DIR" https://raw.githubusercontent.com/Dornila/colonies-pack/main/pack/pack.toml
```

Ноутбук (Lite):
```
"$INST_JAVA" -jar "$INST_MC_DIR/packwiz-installer-bootstrap.jar" --bootstrap-main-jar "$INST_MC_DIR/packwiz-installer.jar" -s client --pack-folder "$INST_MC_DIR" https://raw.githubusercontent.com/Dornila/colonies-pack/main/pack-lite/pack.toml
```
