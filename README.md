# CS333_Final
Final Project for CS333

## Currency Converter (Python Terminal App)

This project is a terminal-based currency converter application built in Python. It allows users to convert between world currencies based on exchange rates relative to USD, update exchange rates, and persist data using a local JSON file.

---

## Features

- Convert from **any supported currency** to **any other** (via USD as intermediary)
- Interactive **text-based UI**
- Preloaded exchange rates from `currencies.json`
- Persistent updates to rates saved across sessions
- Custom exception handling
- Modular structure using clean, testable classes

---

## Testing

Unit and integration testing are implemented using Python’s `unittest` framework 

---

## Coverage

Name                         Stmts   Miss  Cover   Missing
----------------------------------------------------------
converter/converter.py          15      0   100%
converter/currency.py           7       0   100%
converter/registry.py          22      2    91%    17-18
main.py                        50     10    80%    34-38, 41-44
----------------------------------------------------------
TOTAL                          94     12    87%

