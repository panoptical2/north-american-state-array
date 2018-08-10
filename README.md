# north-american-state-array
This is an array containing Canadian, Mexican, and American states/territories and their postal codes.

## Installation
`npm install north-american-state array --save`

## Usage
```angular2html
import { states, stateCodes } from 'north-american-state-array'

console.log(states); // will give you array of full state names
console.log(stateCodes); // will give you array of abbreviated state codes
```

### If you want to just copy/paste the arrays yourself
```angular2html
export const states = ['Aguascalientes', 'Alabama', 'Alaska', 'Alberta', 'Arizona', 'Arkansas', 'Baja California',
    'Baja California Sur', 'British Columbia', 'California', 'Campeche', 'Chiapas', 'Chihuahua', 'Coahuila', 'Colima',
    'Colorado', 'Connecticut', 'Delaware', 'District of Columbia', 'Distrito Federal', 'Durango', 'Florida', 'Georgia',
    'Guanajuato', 'Guerrero', 'Hawaii', 'Hidalgo', 'Idaho', 'Illinois', 'Indiana', 'Iowa', 'Jalisco', 'Kansas', 'Kentucky',
    'Louisiana', 'Maine', 'Maryland', 'Manitoba', 'Massachusetts', 'Mexico', 'Michigan', 'Michoacan', 'Minnesota',
    'Mississippi', 'Missouri', 'Montana', 'Morelos', 'Nayarit', 'Nebraska', 'Nevada', 'New Brunswick', 'New Hampshire',
    'New Jersey', 'New Mexico', 'New York', 'Newfoundland', 'North Carolina', 'North Dakota', 'Northwest Territory',
    'Nova Scotia', 'Nuevo Leon', 'Nunavut', 'Oaxaca', 'Ohio', 'Oklahoma', 'Ontario', 'Oregon', 'Pennsylvania',
    'Prince Edward Island', 'Puebla', 'Puerto Rico', 'Quebec', 'Queretaro', 'Quintana Roo', 'Rhode Island', 'San Luis Potosi',
    'Saskatchewan', 'Sinaloa', 'Sonora', 'South Carolina', 'South Dakota', 'Tabasco', 'Tamaulipas', 'Tennessee', 'Texas',
    'Tlaxcala', 'Utah', 'Veracruz', 'Vermont', 'Virginia', 'Washington', 'West Virginia', 'Wisconsin', 'Wyoming', 'Yucatan',
    'Yukon Territory', 'Zacatecas'];

export const stateCodes = ['AG', 'AL', 'AK', 'AB', 'AZ', 'AR', 'BJ', 'BS', 'BC', 'CA', 'CP', 'CH', 'CI', 'CU', 'CL', 'CO',
    'CT', 'DE', 'DC', 'DF', 'DG', 'FL', 'GA', 'GJ', 'GR', 'HI', 'HG', 'ID', 'IL', 'IN', 'IA', 'JA', 'KS', 'KY', 'LA', 'ME',
    'MD', 'MB', 'MA', 'EM', 'MI', 'MH', 'MN', 'MS', 'MO', 'MT', 'MR', 'NA', 'NE', 'NV', 'NB', 'NH', 'NJ', 'NM', 'NY', 'NF',
    'NC', 'ND', 'NT', 'NS', 'NL', 'NU', 'OA', 'OH', 'OK', 'ON', 'OR', 'PA', 'PE', 'PU', 'PR', 'QC', 'QA', 'QR', 'RI', 'SL',
    'SK', 'SI', 'SO', 'SC', 'SD', 'TA', 'TM', 'TN', 'TX', 'TL', 'UT', 'VZ', 'VT', 'VA', 'WA', 'WV', 'WI', 'WY', 'YC', 'YT', 'ZT'];
```

