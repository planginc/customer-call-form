# Customer Call Automation Form

Automated customer call follow-up form that generates personalized emails using Claude AI and stores complete customer records.

## 🎯 Purpose

This form streamlines the post-call workflow by:
- Collecting minimal customer information (9 fields)
- Processing call transcripts with Claude AI to extract sales intelligence (7 fields)
- Generating personalized follow-up emails with promised resources
- Storing complete customer records in Supabase database

## 🚀 Workflow

1. **User Input**: Fill customer details, URLs, and paste call transcript
2. **N8N Processing**: Form data sent to N8N webhook
3. **Claude Analysis**: AI extracts sales intelligence from transcript
4. **Email Generation**: Personalized follow-up email created with relevant Wild Apricot resources
5. **Data Storage**: Complete customer record stored in Supabase
6. **Dashboard Access**: Generated emails available in Retool dashboard for copy/paste

## 📋 Form Fields

### User Input (9 fields):
- Customer name, email, phone, organization
- HubSpot URL, Zendesk URL, Wild Apricot site URL
- Trial end date
- Call transcript (from Vibe)

### Claude-Extracted (7 fields):
- Notes summary, contact count, go-live timeline
- Next steps, potential blocks, call conclusion
- Promised follow-ups

## 🛠 Tech Stack

- **Frontend**: HTML/CSS/JavaScript form
- **Automation**: N8N workflows
- **AI Processing**: Claude 4 Sonnet via Anthropic API
- **Database**: Supabase PostgreSQL
- **Dashboard**: Retool customer management interface
- **Deployment**: Netlify (auto-deploy from GitHub)

## 🔧 Development Status

**Sprint 1**: ✅ Form design complete with corrected workflow
**Sprint 2**: 🔄 N8N webhook integration
**Sprint 3**: 📋 Claude transcript processing and email generation

## 🔗 Live Demo

[Form will be available here once deployed to Netlify]

---

**Project**: JarvisJr Personal Assistant - Customer Call Automation Module
**Timeline**: Sprint-based development approach
