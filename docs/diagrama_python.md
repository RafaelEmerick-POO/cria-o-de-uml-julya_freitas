# Diagrama UML - Codigo Python

## 1. Arquivos analisados

- `src_python/main.py`
- `src_python/equipamento.py`
- `src_python/sensor_temperatura.py`

## 2. Link do Mermaid Live

Diagrama validado no Mermaid Live.

---
## 3. Diagrama final em Mermaid

```mermaid
classDiagram

class Equipamento {
  -nome
  +ligar()
  +desligar()
}

class SensorTemperatura {
  -temperatura
  +ler_temperatura()
}

Equipamento <|-- SensorTemperatura
```

## 4. Justificativa tecnica

Explique, em frases curtas:

- quais classes foram identificadas;
- como as relacoes aparecem no codigo;
- quais operacoes merecem destaque no diagrama;
- por que seu UML representa corretamente o codigo em `Python`.

## 5. Evidencias

Cole aqui a saida do terminal, prints ou observacoes da execucao do codigo em `Python`.
