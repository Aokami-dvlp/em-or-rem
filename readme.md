REM è l'unità di misura relativa al font-size dell'elemento root <html>
il quale di default è generalmente 16px.

EM è l'unitò di misura relativa al font-size dell'elemento contenitore, e
questo può causare problemi e risultati inaspettati in caso di nesting complessi. 

Misure comunemente usate in rem:

- 2px = 0.125rem (riferimento per operazioni)
- 10px = 0.625rem
- 12px = 0.75rem
- 14px = 0.875rem
- 16px = 1rem (browser default)
- 18px = 1.125rem
- 20px = 1.25rem
- 24px = 1.5rem
- 30px = 1.875rem
- 32px = 2rem

Si può anche applicare il trucco del 62,5% per semplificare le operazioni
matematiche, in modo che la misura indicata corrisponda alla misura in pixel/10.

```
html {
    font-size: 62,5%;
}

h1 {
    font-size: 2rem; (20px)
}

h2 {
    font-size: 1.5rem; (15px)
}

p {
    font-size: 1rem; (10px)
} 
```