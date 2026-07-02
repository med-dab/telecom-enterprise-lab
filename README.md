# Hybrid Telecom Enterprise Network Lab
**Student:** Mohamed Hedi Dab  
**Level:** Master's Degree — Network & Security  
**Year:** 2025/2026

## Architecture
- Multi-Area OSPF (Areas 0,1,2,3-Stub,4-NSSA)
- MPLS Core + iBGP Route Reflector
- eBGP inter-site peering
- VRF Corp/Guest isolation
- BGP MD5 + OSPF MD5 auth
- RPKI + IPsec tunnels
- AWS simulation via Floci (local Docker)

## Tools
GNS3 2.2.59 · FRRouting 8.4 · Floci · KVM · Linux Mint 22.3
