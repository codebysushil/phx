# PHX

> A modern PHP frontend rendering and reactive UI library inspired by JSX, HTMX, Livewire, and server-driven UI concepts.

⚠️ **WARNING: DEVELOPMENT PHASE**
> [!WARNING]
PHX is currently in **active development** and is **NOT production ready** yet.

Features, APIs, folder structure, rendering behavior, and runtime internals may change at any time without backward compatibility.

### Current Status

- Experimental runtime
- Internal APIs may break
- Incomplete documentation
- Performance optimizations in progress
- Security audit not completed
- Some features are unstable or partially implemented

Use this library only for:

- Learning
- Experimentation
- Local projects
- Prototype applications
- Contributing and testing

Do **NOT** use PHX in critical production systems yet.

---

## Features

- JSX-like PHP syntax
- Reactive server-side rendering
- HTMX-friendly architecture
- Zero JavaScript optional components
- Blade-like templating concepts
- Component-based UI
- Lightweight runtime
- PHP-first developer experience

---

## Installation

```bash
composer require sushilk/phx
```

## Example
```php
<?php

use PHX\Component;

class Button extends Component
{
    public function render(): string
    {
        return <<<HTML
            <button class="btn">
                Click Me
            </button>
        HTML;
    }
}
```
