# Corruption Data Nepal 🇳🇵

A collaborative database documenting corruption incidents in Nepal. This repository serves as a transparent, community-driven platform to collect, organize, and share information about corruption cases across various sectors in Nepal.

## 📊 About This Project

This project aims to create a comprehensive, publicly accessible database of corruption incidents in Nepal. The data collected here is consumed by various applications and research projects to promote transparency and accountability.

## 🤝 How to Contribute

We welcome contributions from journalists, researchers, activists, whistleblowers, and concerned citizens. To add a new corruption incident:

1. **Fork this repository**
2. **Add your incident data** to the `incidents.json` file following the schema below
3. **Submit a Pull Request** with a clear description of the incident
4. **Wait for review** - maintainers will verify the data format and approve valid submissions

## 📋 Data Schema

Each incident should follow this JSON structure:

```json
{
  "id": "incident_XXX",
  "title": "Brief descriptive title of the incident",
  "description": "Detailed description of the corruption incident",
  "category": "embezzlement|procurement_fraud|bribery",
  "amount": 0,
  "year": 2024,
  "location": "Specific location in Nepal",
  "officialInvolved": "Names and positions of officials involved",
  "status": "approved|pending|rejected",
  "submittedBy": "Your role/profession (keep anonymous if needed)",
  "submittedAt": "2024-01-01T00:00:00Z",
  "evidence": [
    "list_of_evidence_files.pdf",
    "supporting_documents.xlsx"
  ],
  "links": [
    "https://news-source.com/article",
    "https://official-report.gov.np"
  ],
  "tags": ["relevant", "tags", "for-categorization"]
}
```

### Field Descriptions

- **id**: Unique identifier (use format: `incident_XXX` where XXX is next sequential number)
- **title**: Clear, concise title describing the incident
- **description**: Detailed explanation of what happened
- **category**: Type of corruption - `embezzlement`, `procurement_fraud`, or `bribery`
- **amount**: Financial amount involved (in Nepali Rupees, use 0 if unknown)
- **year**: Year when the incident occurred
- **location**: Geographic location where incident took place
- **officialInvolved**: Names and positions of officials implicated
- **status**: Set to `pending` for new submissions (maintainers will update)
- **submittedBy**: Your role/profession (you can remain anonymous)
- **submittedAt**: Current timestamp in ISO format
- **evidence**: List of supporting documents/evidence (optional)
- **links**: URLs to news articles, reports, or official documents
- **tags**: Relevant keywords for categorization and search

## 📝 Submission Guidelines

### ✅ What We Accept
- Well-documented incidents with credible sources
- Cases reported in reputable media outlets
- Incidents with official investigation reports
- Whistleblower reports with supporting evidence

### ❌ What We Don't Accept
- Unsubstantiated allegations without evidence
- Personal attacks or defamatory content
- Duplicate incidents (please check existing data first)
- Incidents outside Nepal's jurisdiction

### 📋 Before Submitting
1. **Check for duplicates**: Search existing incidents to avoid duplicates
2. **Verify information**: Ensure all details are accurate
3. **Include sources**: Provide credible links and references
4. **Use proper format**: Follow the JSON schema exactly
5. **Protect privacy**: Avoid sharing personal information of victims

## 🔍 Example

See `sample-incidents.json` for examples of properly formatted incident data.

## 📊 Data Usage

This data is used by:
- Transparency and accountability applications
- Research projects on corruption in Nepal
- Journalism and investigative reporting
- Policy analysis and reform initiatives

## 🛡️ Privacy and Safety

- **Whistleblower Protection**: You can contribute anonymously
- **Data Verification**: All submissions are reviewed before approval
- **Source Protection**: We respect the confidentiality of sources
- **Legal Compliance**: All data follows applicable privacy laws

## 📞 Contact

For questions, concerns, or sensitive information:
- Open an issue in this repository
- Contact maintainers through GitHub

## 📄 License

This project is open source. Please see the LICENSE file for details.

## 🙏 Acknowledgments

Thank you to all contributors working towards transparency and accountability in Nepal. Your efforts help build a more transparent society.

---

**Disclaimer**: This repository is for informational and research purposes. All incidents are based on publicly available information and contributor submissions. The maintainers do not guarantee the accuracy of all information and encourage users to verify details independently.
