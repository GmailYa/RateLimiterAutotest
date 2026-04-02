# About
Primo RPA robot uses elements of the package to integrate Allure-Reporting.

# How to Use
In Primo RPA studio, create a project that will be executed by  Primo RPA robot. Install this package via the ".Dependencies -> Manage Dependencies" menu; the "Allure" node with package elements will appear in Elements tree.

The "Test case" element is a container for elements "Test step", "Add Attachment", "Step start", "Step end". This element is used to create test case context and allure report.  
It is not used in pure code.

The "Test step" element is a container for step instance in test case. This element is used to display test step and it's information in Allure-report.  
It is not used in pure code.

The "Add attachment" element is used in "Test case" or "Test step" container. This element is used to display custom attachment (eg. image, csv, xlsx, etc) in Allure-report.  
It is not used in pure code.

The "Step start" element creating test step context (The same functional as "Test step"). This element should be used in pair with "Step end" element.  
It is not used in pure code.

The "Step end" element ending test step context. This element should be used in pair with "Step start" element. 
It is not used in pure code.

# Key Features

- High performance
- Supports .NET Framework 4.6.1+

# Main Types

- Primo.Testing.Allure.Elements.WFTestCase
- Primo.Testing.Allure.Elements.WFStep
- Primo.Testing.Allure.Elements.WFStepStart
- Primo.Testing.Allure.Elements.WFStepEnd
- Primo.Testing.Allure.Elements.WFAddAttachment


# Feedback

Bug reports and contributions are welcome at [Primo RPA chat](https://t.me/primo_RPA_chat)