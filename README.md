# dbt_project_demo

This is a dbt project for demonstrating Snowflake integration and dbt model development.

## Project Structure

- `dbt_project.yml` - dbt project configuration
- `models/` - dbt models
- `macros/` - custom macros
- `seeds/` - seed data files
- `snapshots/` - snapshot definitions
- `tests/` - dbt tests
- `logs/`, `target/` - generated dbt artifacts and logs

## Setup

1. Create and activate your Python virtual environment.
2. Install dbt and any required packages:
   ```powershell
   pip install dbt-core dbt-snowflake
   ```
3. Configure your Snowflake connection in `profiles.yml`.

## Common commands

```powershell
# Compile dbt models
dbt compile

# Run dbt models
dbt run

# Run dbt tests
dbt test
```

## Notes

- Add your Snowflake credentials and profile settings in `~/.dbt/profiles.yml`.
- Exclude `target/`, `logs/`, and other generated files from git using `.gitignore`.
