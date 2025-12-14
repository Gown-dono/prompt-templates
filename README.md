# PromptBox Community Templates

A community-driven collection of prompt templates for PromptBox.

## Structure

```
templates/
├── coding/
│   └── *.json
├── writing/
│   └── *.json
├── analysis/
│   └── *.json
└── ...
```

## Template Format

Each template is a JSON file with this structure:

```json
{
  "id": "unique-template-id",
  "title": "Template Title",
  "category": "Category Name",
  "tags": ["tag1", "tag2"],
  "content": "The actual prompt template content...",
  "description": "Brief description of what this template does",
  "author": "Author Name",
  "version": "1.0",
  "submittedBy": "github-username",
  "submittedDate": "2025-12-14T00:00:00Z",
  "lastUpdated": "2025-12-14T00:00:00Z",
  "dependencies": [],
  "licenseType": "MIT"
}
```

## Contributing

1. Fork this repository
2. Create a new JSON file in the appropriate category folder
3. Follow the template format above
4. Submit a Pull Request

## License

Templates are contributed under their specified licenses (MIT, CC0, CC-BY, etc.)
