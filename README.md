# NetPractice - Network Configuration and Subnetting

## About

**NetPractice** is a networking fundamentals project at École 42 that focuses on understanding TCP/IP networking, subnetting, and network configuration. The project involves solving a series of network configuration challenges that require knowledge of IP addressing, subnet masks, routing tables, and network topology design.

This project provides hands-on experience with essential networking concepts that form the foundation of modern network administration, DevOps practices, and system infrastructure management.

## Learning Objectives

- **IP Addressing**: Understanding IPv4 addressing schemes and address classes
- **Subnetting**: Mastering subnet masks, CIDR notation, and network segmentation
- **Routing**: Configuring routing tables and understanding packet forwarding
- **Network Topology**: Designing and analyzing network architectures
- **OSI Model**: Practical application of network layer concepts
- **Network Troubleshooting**: Identifying and resolving network connectivity issues
- **CIDR Notation**: Understanding Classless Inter-Domain Routing principles

## Core Networking Concepts

### IP Addressing Fundamentals

#### IPv4 Address Structure
- **32-bit addresses**: Represented in dotted decimal notation (e.g., 192.168.1.1)
- **Network and Host portions**: Determined by subnet mask
- **Address classes**: Understanding Class A, B, and C networks
- **Private vs Public**: RFC 1918 private address ranges

#### Subnet Masks and CIDR
- **Subnet mask purpose**: Defining network and host boundaries
- **CIDR notation**: Compact representation (e.g., /24, /16, /8)
- **Network calculations**: Determining network range, broadcast, and host addresses
- **Variable Length Subnet Masks (VLSM)**: Efficient IP address utilization

### Network Topology Elements

#### Network Devices
- **Routers**: Layer 3 devices for inter-network communication
- **Switches**: Layer 2 devices for local network connectivity
- **Interfaces**: Physical and logical connection points
- **Default Gateways**: Router interfaces for external network access

#### Routing Tables
- **Destination networks**: Target network addresses
- **Next hop addresses**: Router interfaces for packet forwarding
- **Interface assignments**: Physical interfaces for packet transmission
- **Default routes**: Catch-all routing for unknown destinations

## Project Structure and Challenges

### Level Progression
The NetPractice project consists of 10 progressive levels, each increasing in complexity:

#### Basic Levels (1-3)
- **Simple subnetting**: Basic subnet mask calculations
- **Point-to-point links**: Direct router connections
- **Basic routing**: Simple routing table configuration

#### Intermediate Levels (4-7)
- **Complex topologies**: Multi-router network designs
- **VLSM implementation**: Variable subnet sizes
- **Multiple networks**: Interconnected network segments
- **Advanced routing**: Multi-path routing scenarios

#### Advanced Levels (8-10)
- **Enterprise scenarios**: Large-scale network designs
- **Complex routing tables**: Multiple destination networks
- **Optimization challenges**: Efficient IP address utilization
- **Troubleshooting scenarios**: Identifying configuration errors

### Challenge Types

#### IP Address Configuration
- **Host addressing**: Assigning valid IP addresses to network interfaces
- **Subnet calculations**: Determining correct subnet boundaries
- **Address conflicts**: Avoiding duplicate IP assignments
- **Range validation**: Ensuring addresses fall within subnet ranges

#### Subnet Design
- **Network segmentation**: Creating appropriately sized subnets
- **CIDR planning**: Optimal subnet mask selection
- **Address space efficiency**: Minimizing IP address waste
- **Scalability considerations**: Planning for future growth

#### Routing Configuration
- **Static routing**: Manual route table entries
- **Default gateways**: Configuring gateway addresses
- **Route prioritization**: Understanding routing precedence
- **Path determination**: Selecting optimal packet paths

## Technical Implementation

### CIDR and VLSM Strategies

#### Subnet Size Planning
- **Host requirement analysis**: Determining needed host addresses per subnet
- **Growth planning**: Allocating space for future expansion
- **Efficient allocation**: Minimizing wasted address space
- **Hierarchical design**: Creating logical network hierarchies

#### VLSM Implementation
Variable Length Subnet Masking allows efficient use of IP address space:
- **Different subnet sizes**: /30 for point-to-point, /24 for LANs
- **Address conservation**: Allocating only needed addresses
- **Route summarization**: Reducing routing table size
- **Flexible design**: Adapting to varying network requirements

### Routing Table Configuration

#### Route Selection Process
1. **Longest prefix match**: Most specific route takes precedence
2. **Administrative distance**: Route source reliability
3. **Metric comparison**: Cost-based route selection
4. **Load balancing**: Equal-cost path utilization

## Troubleshooting Techniques

### Common Configuration Errors

#### IP Address Conflicts
- **Same subnet assignment**: Multiple devices with identical addresses
- **Overlapping subnets**: Subnet ranges that intersect
- **Invalid host addresses**: Using network or broadcast addresses
- **Gateway misconfiguration**: Incorrect default gateway assignment

#### Routing Issues
- **Missing routes**: No path to destination networks
- **Incorrect next-hop**: Wrong router interface specification
- **Interface mismatches**: Route interface doesn't match topology
- **Default route problems**: Missing or incorrect default routes

#### Subnet Mask Errors
- **Inconsistent masks**: Different masks on same network
- **Wrong subnet size**: Mask doesn't accommodate required hosts
- **CIDR notation errors**: Incorrect prefix length specification
- **Calculation mistakes**: Mathematical errors in subnet planning

## Key Challenges & Solutions

### Efficient Subnet Design
- **Challenge**: Optimizing IP address space utilization while meeting host requirements
- **Solution**: VLSM implementation with careful subnet size planning

### Complex Routing Scenarios
- **Challenge**: Configuring routing tables for multi-path, multi-network environments
- **Solution**: Systematic routing analysis with longest-prefix-match understanding

### Network Scalability
- **Challenge**: Designing networks that accommodate future growth
- **Solution**: Hierarchical addressing with reserved address space

### Troubleshooting Connectivity
- **Challenge**: Identifying root causes of network connectivity failures
- **Solution**: Methodical layer-by-layer analysis using OSI model approach

## Skills Demonstrated

- **Network Design**: Ability to design efficient, scalable network topologies
- **Subnetting Mastery**: Advanced subnet planning and VLSM implementation
- **Routing Knowledge**: Understanding of routing protocols and table configuration
- **Problem-Solving**: Systematic approach to network troubleshooting
- **Mathematical Skills**: Accurate binary/decimal conversion and network calculations
- **Documentation**: Clear network documentation and configuration management
- **Standards Knowledge**: Understanding of networking standards and best practices

## Real-World Applications

The networking knowledge gained from NetPractice is essential for:
- **Network Administration**: Managing enterprise network infrastructure
- **Cloud Computing**: Understanding virtual network configuration in AWS, Azure, GCP
- **DevOps**: Container networking, Kubernetes cluster networking
- **System Administration**: Server network configuration and troubleshooting
- **Security**: Network segmentation and security boundary implementation
- **Infrastructure as Code**: Automated network provisioning and management

## Professional Relevance

### Career Paths
- **Network Engineer**: Designing and maintaining network infrastructure
- **Systems Administrator**: Managing server and network connectivity
- **DevOps Engineer**: Implementing infrastructure automation and orchestration
- **Cloud Architect**: Designing cloud-native networking solutions
- **Security Engineer**: Implementing network-based security controls

### Industry Applications
- **Data Centers**: Large-scale network design and management
- **Enterprise Networks**: Corporate network planning and implementation
- **Service Providers**: ISP and telecommunications network design
- **Cloud Platforms**: Virtual network configuration and optimization
- **IoT Networks**: Internet of Things device networking

## Notes

NetPractice provides essential networking foundation knowledge that underlies much of modern IT infrastructure. The project emphasizes practical problem-solving skills that are immediately applicable in professional networking environments.

The systematic approach to network design and troubleshooting developed through this project is valuable for understanding more complex networking topics like BGP, OSPF, VLANs, and advanced routing protocols.

---

*Developed as part of the École 42 curriculum - building essential networking knowledge through practical subnetting and routing challenges.*
