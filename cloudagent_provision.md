


`
aca-py start   --label CA --inbound-transport http 0.0.0.0 8040   --outbound-transport http   --admin 0.0.0.0 8021   --admin-insecure-mode   --genesis-url http://localhost:9000/genesis   --seed CAEnd123000000000000000000000000   --wallet-type indy --wallet-name CAEnd --wallet-key walletkey1 --endpoint http://localhost:8040/   --public-invites   --auto-provision   --auto-accept-invites   --auto-accept-requests   --auto-ping-connection   --monitor-ping   --debug-connections
`


`
aca-py start   --label Alice --inbound-transport http 0.0.0.0 8060   --outbound-transport http   --admin 0.0.0.0 8041   --admin-insecure-mode   --genesis-url http://localhost:9000/genesis   --seed pjaW3r9QhqJRRXMU3JtB1E38ttFkRg6q  --wallet-type indy --wallet-name Alice --wallet-key walletkey2 --endpoint http://localhost:8060/   --public-invites   --auto-provision   --auto-accept-invites   --auto-accept-requests   --auto-ping-connection   --monitor-ping   --debug-connections --auto-respond-credential-offer --auto-store-credential
`
