# Designing an HR Database

You are the new data architect at **Tech ABC Corp**, a fast-growing video game company. The HR department has outgrown its employee spreadsheet and has asked you to design, build, and populate a proper relational database. In this project you'll take that request from raw requirements all the way to a working, populated database in AWS.

## Getting Started

1. Open **`Starter_File.ipynb`** in the project workspace
2. Work through the notebook top to bottom — each section maps to a project step below.
3. Grab your database credentials from the **Cloud Resources** tab when you reach the AWS connection step.

### Dependencies

The workspace comes preloaded with everything you need:

```
pandas, openpyxl, psycopg2, boto3
```

### Files in this repo

| File | Purpose |
|------|---------|
| `Starter_File.ipynb` | Scaffolded notebook — your starting point |
| `HR_Dataset_V2.xlsx` | Source HR data (employee records, 15 columns) |

## Project Steps

1. **Data Architecture Foundations** — turn the HR request into a business proposal and a technical proposal.
2. **Relational Database Design** — build conceptual, logical, and physical ERDs in Mermaid, normalized to 3NF.
3. **Data Contract** — define `data_contract.json`, validate the Excel data against it in Python, and load the validated records into an AWS landing table.
4. **Create a Physical Database** — build your 3NF tables with DDL, populate them from the landing table, and answer the CRUD questions.
5. **Above and Beyond** *(optional)* — add a view, a stored procedure, and user-level security on salary data.

## Deliverables

Submit the following from the project workspace:

- Your completed notebook (all steps, with code run and output visible).
- Your **`data_contract.json`** file (a new file you will create).

## Rubric

Before submitting, review your work against the **project rubric** in the classroom to confirm you've met every requirement.

## License

[License](LICENSE.txt)
