# Ledger-API

## About
SpringBoot application with Spring Data, Spring Web, Thymeleaf & H2 Database

Java API, a ledger between 2 people. +/- values posted as @RequestParam which represent transactions between them.

## Photos

![ledger application](/assets/ledger.JPG)

![ledger usage in postman](/assets/ledger-postman.JPG)


Notatki:
- W Controller'ach nie używam @RestController, bo w argumencie metody przyjmuję @RequestParam zamiast @RequestBody, a zamiast @ResponseBody zwracam Template generowany przez Spring wykorzystując framework Thymeleaf.
