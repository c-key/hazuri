# Hazuri

**Your personal collection of URIs.**

Hazuri is a lightweight, self-hosted application for collecting and
organizing URIs in one place.

**Unlike a traditional bookmark manager, Hazuri isn't limited to web URLs.**

Store web links, email addresses, telephone links, and other URI schemes
without turning your personal collection into a complex service.

Hazuri keeps things simple: minimal dependencies, portable SQLite storage,
and data that remains under your control.

## Why Hazuri?

Bookmarks are only one kind of URI.

Hazuri treats `https:`, `mailto:`, `tel:` and other URI schemes as
first-class entries, allowing every user to maintain their own personal
collection.

The name **Hazuri** is a coined name inspired by *hazina*
(Swahili: treasure) and **URI** (Uniform Resource Identifier).

## Architecture

**Hazuri is a small, portable home for your URIs.**

The architecture is intentionally simple. Hazuri uses PHP and SQLite to
provide a lightweight, self-contained application that can be deployed
without a complex infrastructure.

Its core principles are:

- **Minimal dependencies** — keep the application stack small and
  understandable.
- **SQLite storage** — keep the collection in a portable, file-based
  database.
- **Self-hosted** — your collection and data remain under your control.
- **Per-user collections** — every user maintains their own URI collection.
- **URI-scheme agnostic** — `https:`, `mailto:`, `tel:` and other schemes
  are treated as first-class entries.
- **Portable by design** — moving or backing up Hazuri should remain simple.
