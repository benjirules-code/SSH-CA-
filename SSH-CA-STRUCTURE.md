ssh-ca-lab/
│
├── README.md
│
├── ca/
│   ├── generate_ca.sh
│   ├── ssh_ca
│   └── ssh_ca.pub
│
├── users/
│   ├── generate_user_key.sh
│   ├── user_key
│   ├── user_key.pub
│   └── user_key-cert.pub
│
├── server/
│   ├── sshd_config.example
│   ├── trusted_user_ca_keys.pub
│   └── notes.md
│
├── examples/
│   ├── sign_user_cert.sh
│   ├── revoke_example.krl
│   └── verify_cert_output.txt
│
└── docs/
    ├── ssh_handshake_diagram.png
    ├── ssh_ca_flow.png
    └── slides/
        └── SSH_CA_Presentation.pdf
