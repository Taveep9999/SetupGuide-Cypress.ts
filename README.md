# SetupGuide-Cypress.ts  
npm init -y  
npm install cypress typescript @types/node cypress-xpath @faker-js/faker --save-dev  
npx cypress open  
 
Replace config file  
cypress.config  
e2e  
tsconfig  
scripts in package  
 
//when use faker or other plugin  
import { faker } from '@faker-js/faker';  
