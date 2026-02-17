# hybrid-enterprise-core

## Description
A modular repo demonstrating enterprise integration between mainframe systems (COBOL, JCL, DB2) and cloud services (Java, REST APIs). Designed to showcase scalable, secure, and maintainable architecture for modernizing legacy transaction and loyalty platforms.

This codebase enables iterative modernization of legacy systems. 

> This is a public, sanitized portfolio. No credentials or proprietary code included.

## Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/...
   ```
2. Install dependencies:
   - Java: Ensure JDK 11+ and Gradle are installed
   - COBOL: Install GnuCOBOL for local compilation (optional)
   - DB2: Set up a local or remote DB2 instance

3. Configure environment variables:
   - Create a `.env` file with database credentials and service endpoints
## Usage
- **Mainframe Layer**: Compile and run COBOL programs using provided JCL scripts
- **Cloud Services**: Start the Spring Boot API with `./gradle bootRun`
- **Integration**: Use the REST bridge to connect cloud services to mainframe data



# Develop and deploy production-grade ML models and AI systems for diagnostics