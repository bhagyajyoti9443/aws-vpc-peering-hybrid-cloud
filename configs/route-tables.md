## Route Table Configuration

### VPC-1 Route Table
- Destination: 172.16.0.0/16
- Target: VPC Peering Connection

### VPC-2 Route Table
- Destination: 10.0.0.0/16
- Target: VPC Peering Connection

### Notes
- No internet gateway used for inter-VPC traffic
- Traffic flows privately over AWS backbone
