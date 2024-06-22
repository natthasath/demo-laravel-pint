# 🎉 DEMO Laravel Pint

Laravel Pint is a lightweight PHP framework designed for rapid web application development, emphasizing simplicity and elegance. It offers robust features like routing, ORM, authentication, and templating, making it ideal for building scalable and maintainable web projects with ease.

![version](https://img.shields.io/badge/version-1.0-blue)
![rating](https://img.shields.io/badge/rating-★★★★★-yellow)
![uptime](https://img.shields.io/badge/uptime-100%25-brightgreen)

### 🚀 Setup

- Install Package

```shell
composer require laravel/pint --dev
```

- Create `pint.json`

```json
{
    "preset": "laravel",
    "rules": {
        "array_indentation": true,
        "binary_operator_spaces": {
            "default": "single_space"
        },
        "blank_line_after_namespace": true,
        "blank_line_after_opening_tag": true,
        "blank_line_before_statement": {
            "statements": ["return"]
        },
        "braces": {
            "position_after_control_structures": "same",
            "position_after_functions_and_oop_constructs": "next",
            "position_after_anonymous_constructs": "same"
        },
        "concat_space": {
            "spacing": "one"
        },
        "method_argument_space": {
            "on_multiline": "ensure_fully_multiline"
        },
        "phpdoc_to_comment": false,
        "no_unused_imports": true,
        "no_whitespace_in_blank_line": true
    }
}

```

- Run Pint

```shell
./vendor/bin/pint
```

### 🏆 Run

- [http://localhost:8000](http://localhost:8000)

```shell
php artisan serve
```
