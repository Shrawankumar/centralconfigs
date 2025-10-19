# centralconfigs

# Example: order service is looking for config with profile dev
order it follow to look up property

 orders-service-dev.properties -> application-dev.properties -> order-service.properties -> application.properties

-> application-dev.properties (order service application local)
-> applcation.properties (order service application local)

# Global / Common properties
- application.properties (applies to all service and all profiles like dev, qa or prod etc.)
- application-{profile}.properties (applied to all service with specific profile dev or qa)

# order service properties
- application.properties (applies to specific service and all profiles like dev, qa or prod etc.)
- application-{profile}.properties (applied to all service with specific profile dev or qa)