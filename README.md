# Life Is A Game

This email template for the Sports & Entertainment industry promotes a unique concept of life being compared to a game, using engaging visuals and persuasive language to attract subscribers.

![Thumbnail](./thumbnail.png)

## Template Details

- **Industries:** Sports & Entertainment
- **Message Type:** Marketing
- **Tags:** sports, game, life

## Files
- `index.html`: The improved, localized, and branded HTML template.
- `template.blade.php`: Ready-to-use Laravel Blade template with `asset()` helpers.
- `assets/`: Directory containing localized images and styles used in the template.

## Usage in Laravel

### 1. Store the Template
Place the `index.html` content in a Blade view (e.g., `resources/views/emails/life-is-a-game.blade.php`).

### 2. Handle Assets
Move the content of `assets/` to your public directory (e.g., `public/vendor/mail-templates/life-is-a-game/`) and update the paths in the HTML to use the `asset()` helper.

### 3. Send Email
```php
Mail::to($user)->send(new \App\Mail\GenericEmail([
    'view' => 'emails.life-is-a-game',
    'data' => [
        // Your dynamic data here
    ]
]));
```

---
*Created with ❤️ by **[LaravelMail.com](https://laravelmail.com)** - Your source for professional email templates.*
