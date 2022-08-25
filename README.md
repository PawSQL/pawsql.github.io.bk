<p align="center">
  <a href="https://www.pawsql.com/">
    <img src="https://pawsql.github.io/assets/images/rls180.png" width="320" alt="Optimize by One Click">
  </a>
</p>

<p align="center">
  <strong>
    <a href="https://pawsql.github.io/">PawSQL</a> 
    optimizes SQL queries by One Click
  </strong>
</p>

# PawSQL Advisor

In addition to integrating the powerful index recommendation function of [Paw Index Advisor], PawSQL Advisor also integrates the industry's best practices for query optimization for relational databases, and audits and rewrites SQL capatility from the aspects of correctness and performance. PawSQL Advisor is integrated with the most popular IDE, such as IntelliJ IDEA , PhpStorm, PyCharm , WebStorm. It helps database application developers and database administrator optimize their queries by ***One Click***. 

## Features

 - [Rules-based SQL auditing], targeting correctness auditing and performance optimization.
 - [Rewrite optimization], recommended semantically equivalent, but more efficient SQL.
 - Intelligent [index recommendation], based on input SQL syntax, database objects and statistics information.
 - [What-if validation] to ensure gaining better performance after SQL rewriting and indexing recommendations.

## Get started

 - Start the JetBrains integrated development environment(IntelliJ IDEA, CLion, PyCharm and etc,), open the project Setting, select Plugins;
 - Enter "PawSQL Advisor" in Marketplace and click Install;
 - [Configure] the running parameters of PawSQL Advisor on the Setting page;
 - Right-click on the SQL file or folder to be analyzed, and click "Run PawSQL Advisor";
 - Wait for a while and the [optimization recommendations] will be presented to you.

# Paw Index Advisor

Paw Index Advisor is an automatic and intelligent cost-based index recommendation tool for MySQL and PostgreSQL databases. Paw Index Advisor is integrated with the most popular IDE, such as IntelliJ IDEA , PhpStorm, PyCharm , WebStorm. It helps database application developers and database administrator optimize their queries by ***One Click***. 

## Features

+ Combination of cost based and heuristic algorithm based
+ Support MySQL and PostgreSQL and derivatives, such as Opengauss, Maria
+ Support index recommendation covering matching, screening, sort-avoiding,covering
+ De-duplicate with existing indexes
+ Support query rewrites, sattc, view folding, and ordinal rewrite
+ Client-based, non-invasion to production system
+ Support [what-if validation], make sure indexes recommended be used in later query execution

## Get started

 - Start the JetBrains IDE(IntelliJ IDEA, CLion, PyCharm and etc), open the project Setting, select Plugins;
 - Enter [`Paw Index Advisor`] in martketplace and click install
 - [Configure] the running parameters of Paw Index Advisor on the Setting page
 - Right click on the SQL file or folder to be analyzed, and click "Run Index Advisor"
 - Wait for minutes and [recommended indexes] will be presented to you to accelerate your database queries.


 __Claim:__ PawSQL Advisor and Paw Index Advisor is delivered as a beta version for free trial.  You are welcomed to file bugs at https://pawsql.youtrack.cloud/newIssue.

[Paw Index Advisor]: https://www.pawsql.com/pawindexadvisor/getstarted/
[Configure]: https://www.pawsql.com/pawsqladvisor/configuration/
[optimization recommendations]: https://www.pawsql.com/pawsqladvisor/pawsummary/
[pawSummary.sql]: https://www.pawsql.com/pawsqladvisor/getstarted/
[what-if validation]: https://www.pawsql.com/pawindexadvisor/what-if-validation/
[recommended indexes]: https://www.pawsql.com/pawindexadvisor/recommended-indexes/
[`Paw Index Advisor`]: https://plugins.jetbrains.com/plugin/19003-paw-index-advisor
[Rules-based SQL auditing]: http://127.0.0.1:8000/pawreference/audit-rules/
[Rewrite optimization]: http://127.0.0.1:8000/pawreference/rewrite-rules/
[index recommendation]: https://www.pawsql.com/pawindexadvisor/recommended-indexes/
