curl -LsS https://ai.snowflake.com/static/cc-scripts/install.sh | sh
export PATH="$HOME/.local/bin:$PATH"
mkdir -p ~/.snowflake
nano ~/.snowflake/connections.toml
[myconn]
account = "<>"
user = "<>"
authenticator = "externalbrowser"
role = "<>"
warehouse = "TEST_DW"
database = "PK_DB"
schema = "PUBLIC"
