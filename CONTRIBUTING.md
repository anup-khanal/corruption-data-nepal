# Contributing to Corruption Data Nepal

Thank you for your interest in contributing to the Corruption Data Nepal project! Your contributions help build transparency and accountability in Nepal.

## 🚀 Quick Start

1. **Fork** this repository
2. **Clone** your fork locally
3. **Add** your incident data to `incidents.json`
4. **Commit** your changes with a descriptive message
5. **Push** to your fork
6. **Submit** a Pull Request

## 📋 Detailed Contribution Process

### Step 1: Prepare Your Data

Before adding an incident, ensure you have:
- ✅ Verified the incident is not already in the database
- ✅ Gathered credible sources and evidence
- ✅ Prepared all required information per the schema
- ✅ Reviewed our submission guidelines

### Step 2: Format Your Data

Use the exact JSON schema from the README:

```json
{
  "id": "incident_XXX",
  "title": "Brief descriptive title",
  "description": "Detailed description of the incident",
  "category": "embezzlement|procurement_fraud|bribery",
  "amount": 0,
  "year": 2024,
  "location": "Location in Nepal",
  "officialInvolved": "Names and positions",
  "status": "pending",
  "submittedBy": "Your role/profession",
  "submittedAt": "2024-01-01T00:00:00Z",
  "evidence": ["file1.pdf", "file2.xlsx"],
  "links": ["https://source1.com", "https://source2.com"],
  "tags": ["tag1", "tag2", "tag3"]
}
```

### Step 3: Add to incidents.json

1. Open `incidents.json`
2. Add your incident object to the array
3. Ensure proper JSON formatting (commas, brackets, etc.)
4. Validate JSON syntax before submitting

### Step 4: Submit Pull Request

Use our PR template and provide:
- Clear title describing the incident
- Summary of the corruption case
- Sources and evidence links
- Confirmation of data accuracy

## 🔍 Data Quality Standards

### Required Information
- **Credible Sources**: At least one reputable news source or official document
- **Accurate Details**: Verified names, dates, amounts, and locations
- **Proper Category**: Must be embezzlement, procurement_fraud, or bribery
- **Complete Schema**: All required fields must be filled

### ID Assignment
- Use format: `incident_XXX` where XXX is the next sequential number
- Check existing incidents to determine the next available ID
- Example: If last incident is `incident_012`, use `incident_013`

### Status Field
- Always set `status` to `"pending"` for new submissions
- Maintainers will update to `"approved"` or `"rejected"` after review

### Amount Field
- Use Nepali Rupees (NPR) as the currency
- If exact amount is unknown, use `0`
- Do not include currency symbols in the number

## 📝 Writing Guidelines

### Titles
- Keep concise but descriptive (under 100 characters)
- Use title case
- Avoid sensational language
- Example: "Ministry of Health Medical Equipment Overpricing Scandal"

### Descriptions
- Provide factual, objective descriptions
- Include key details: what happened, when, where, who was involved
- Avoid speculation or unverified claims
- Minimum 100 characters, maximum 1000 characters

### Evidence and Links
- Include URLs to news articles, government reports, or official documents
- Ensure links are accessible and not behind paywalls when possible
- List evidence files even if you don't have direct access to them

## 🛡️ Safety and Privacy

### Protecting Sources
- You can contribute anonymously by using generic roles (e.g., "Journalist", "Government Employee")
- Do not include personal contact information
- Respect confidentiality of sensitive sources

### Legal Considerations
- Only include information that is already public or officially reported
- Avoid defamatory language
- Stick to facts and verified information
- Include disclaimers when information is alleged

## ❌ Common Mistakes to Avoid

1. **Invalid JSON**: Always validate your JSON syntax
2. **Duplicate IDs**: Check existing incidents for ID conflicts
3. **Missing Required Fields**: Ensure all schema fields are present
4. **Incorrect Categories**: Use only the three specified categories
5. **Unverified Information**: Include only credible, sourced information
6. **Personal Attacks**: Focus on facts, not personal opinions

## 🔄 Review Process

### What Happens After Submission
1. **Automated Checks**: JSON validation and format verification
2. **Content Review**: Maintainers verify sources and accuracy
3. **Feedback**: You may receive requests for clarification or corrections
4. **Approval**: Valid submissions are merged into the main database

### Timeline
- Initial review: 3-7 business days
- Feedback response: 2-3 business days
- Final approval: 1-2 business days after corrections

## 🆘 Getting Help

### Before Asking for Help
- Check existing issues for similar questions
- Review the README and this contributing guide
- Validate your JSON syntax using online tools

### How to Get Help
- **General Questions**: Open a GitHub issue with the "question" label
- **Technical Issues**: Open a GitHub issue with the "bug" label
- **Sensitive Information**: Contact maintainers privately through GitHub

### Issue Templates
Use our issue templates for:
- 🐛 Bug reports
- ❓ Questions
- 💡 Feature requests
- 📊 Data corrections

## 🏆 Recognition

Contributors will be acknowledged in:
- GitHub contributor list
- Annual transparency reports
- Project documentation

## 📄 Code of Conduct

By participating in this project, you agree to:
- Provide accurate, factual information
- Respect privacy and confidentiality
- Use respectful, professional language
- Follow all contribution guidelines
- Support the project's transparency goals

## 🔄 Updating Existing Data

If you find errors in existing incidents:
1. Open an issue describing the problem
2. Provide corrected information with sources
3. Wait for maintainer review before making changes

## 📊 Data Validation Tools

Before submitting, validate your JSON:
- [JSONLint](https://jsonlint.com/)
- [JSON Formatter](https://jsonformatter.curiousconcept.com/)
- VS Code with JSON validation extensions

Thank you for contributing to transparency and accountability in Nepal! 🇳🇵
