[titleEn]: <>(SalesChannel-API context endpoint)

The `context` endpoint is used to obtain information about various entities like currency, language or country which are assigned to a
sales channel.

## Get salutations

**GET  /sales-channel-api/v1/salutation**

**Response:** Returns a list of salutations defined in the settings of your shop.

## Get currencies

**GET  /sales-channel-api/v1/currency**

**Response:** Returns a list of currencies assigned to the sales channel.
All filter, sorting, limit, and search operations are supported.
You find more information about these operations [here](./050-filter-search-limit.md).

## Get languages

**GET  /sales-channel-api/v1/language**

**Response:** Returns a list of languages assigned to the sales channel.
All filter, sorting, limit, and search operations are supported.
You find more information about these operations [here](./050-filter-search-limit.md).

## Get countries

**GET  /sales-channel-api/v1/country**

**Response:** Returns a list of countries assigned to the sales channel.
All filter, sorting, limit, and search operations are supported.
You find more information about these operations [here](./050-filter-search-limit.md).

## Get country states

**GET  /sales-channel-api/v1/country/{countryId}/state**

**Response:** Returns a list of country states assigned to the sales channel and country.
All filter, sorting, limit, and search operations are supported.
You find more information about these operations [here](./050-filter-search-limit.md).

## Get payment methods

**GET  /sales-channel-api/v1/payment-method**

**Header:** sw-context-token is required  
**Response:** Returns a list of payment methods assigned to the sales channel.
All filter, sorting, limit, and search operations are supported.
You find more information about these operations [here](./050-filter-search-limit.md).

## Get shipping methods

**GET  /sales-channel-api/v1/shipping-method**

**Header:** sw-context-token is required  
**Response:** Returns a list of shipping methods assigned to the sales channel.
All filter, sorting, limit, and search operations are supported.
You find more information about these operations [here](./050-filter-search-limit.md).
