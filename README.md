meme_dict = {
            "CRINGE": "Algo excepcionalmente raro o embarazoso",
            "LOL": "Una respuesta común a algo gracioso",
            "CREEPY": "algo aterrador o siniestro",
            "BRO": "un amigo o compañero",
            "MEME": "imagen o video humorístico que circula por internet"
            }
print("Este es un diccionario para palabras que no entiendas para darte su significado")
for i in range(5):
    word = input("Escribe una palabra que no entiendas (¡con mayúsculas!): ")
    if word in meme_dict.keys():
        print(meme_dict[word])
    else:
        print("Esta palabra no está en el diccionario.")
