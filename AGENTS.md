## Security

Security model: [SECURITY.md](./SECURITY.md), which links to the project's
threat model at
[site/_docs/security_threat_model.md](./site/_docs/security_threat_model.md).

Avatica is a JDBC/ODBC wire-protocol layer: a server that fronts a
local JDBC `DataSource` (typically Apache Calcite, but any JDBC driver
is supported), and a client-side JDBC driver that speaks the Avatica
wire protocol over HTTP or HTTPS.
