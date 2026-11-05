# 📚 BibliothequeDigitale

A C# (.NET 6) console application that models a digital library with a clean object-oriented design.

> 🇫🇷 **Français :** Application console C# (.NET 6) modélisant une bibliothèque numérique avec une conception orientée objet propre.

## What it demonstrates

- **OOP inheritance** — a `Document` base class extended by `Livre` (book), `Magazine`, and `DocumentPDF`
- **Custom exceptions** — `DocumentNonTrouveException` for missing-document handling
- **Separation of concerns** — `Bibliotheque` manages the collection; `Program` handles the console menu and UI

## Structure

```
dotnet/
├── Document.cs                   # Base class
├── Livre.cs                      # Book
├── Magazine.cs                   # Magazine
├── DocumentPDF.cs                # PDF document
├── Bibliotheque.cs               # Library manager
├── DocumentNonTrouveException.cs # Custom exception
├── Program.cs                    # Console entry point
└── BibliothequeDigitale.csproj
```

## Run

```bash
cd dotnet
dotnet run
```

## License

[MIT](LICENSE)
