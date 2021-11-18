# Standards and Models of Library Metadata

## Dublin Core(DC)|都柏林核心

### [DCMI Metadata Terms](http://dublincore.org/documents/2012/06/14/dcmi-terms/?v=terms)

Dublin Core Metadata Element Set

### [DCMES｜都柏林核心元数据元素集](http://dublincore.org/documents/dces/)

- Simple DC｜简单都柏林核心

	- 15 Elements

		- Title
		- Creator
		- Description
		- Subject
		- Publisher
		- Contributor
		- Date
		- Type
		- Format
		- Source
		- Language
		- Relation
		- Identifier
		- Coverage
		- Rights

- Qualified DC｜扩展都柏林核心

	- 3 Additional Elements

		- Audience
		- Provenance
		- RightsHolder

	- Element Refinements（Qualifiers）

		- Alternative
		- Table Of Contents
		- Abstract
		- Created
		- Valid
		- Available
		- Issued
		- Modified
		- Date Accepted
		- Date Copyrighted
		- Date Submitted
		- Extend
		- Medium
		- Bibliographic Citation
		- Is Version Of
		- Has Version
		- Is Replaced By
		- Replace
		- Is Required By
		- Requires
		- Is Part Of
		- Has Part
		- Is Referenced By
		- References
		- Is Format Of
		- Has Format
		- Conforms To
		- Spatial
		- Temporal
		- Access Rights
		- License

### DCMI (DC Metadata Initiative)｜都柏林核心元数据启动计划

- An open organization

	- 致力于开发可互操作的元数据标准

		- 应用于多种目的和商业模型

	- 活动

		- 架构和建模
		- DCMI 社区和课题组内的讨论和协作
		- 年度会议
		- 相关标准联络人
		- 培训推广标准和实践经验

### [DCAM (DCMI Abstract Model)｜都柏林核心抽象模型](http://dublincore.org/documents/abstract-model/)

- Purpose

	- to specify the components and constructs used in Dublin Core metadata. It defines the nature of the components used and describes how those components are combined to create information structures. It provides an information model which is independent of any particular encoding syntax. Such an information model allows us to gain a better understanding of the kinds of descriptions that we are encoding and facilitates the development of better mappings and cross-syntax translations.

- Who uses DCAM

	- aimed at the developers of software applications that support Dublin Core metadata, people involved in developing new syntax encoding guidelines for Dublin Core metadata and people developing metadata application profiles based on DCMI vocabularies or on other compatible vocabularies.

## [ISBD｜国际标准书目著录](http://www.ifla.org/publications/international-standard-bibliographic-description)

## Functional Requirements for Bibliographic Records（FRBR） Family

### FRBR｜书目记录的功能需求

Also be referred as FRBRer while talking FRBRoo

- Definition

	- Functional Requirements for Bibliographic Records
	- is a conceptual entity-relationship model developed by the International Federation of Library Associations and Institutions (IFLA) that relates user tasks of retrieval and access in online library catalogues and bibliographic databases from a user’s perspective. It represents a more holistic approach to retrieval and access as the relationships between the entities provide links to navigate through the hierarchy of relationships.

- Relationships

	- Equivalence｜相等物

		- Copies
		- Issues
		- Facsimiles
		- Reprints
		- Photocopies
		- Microfilms

	- Derivative｜衍生物

		- Editions
		- Translations
		- Digests
		- 对原作进行的改编
		- 形式变更
		- 基于原作风格或主题的新创作

	- Descriptive｜描写

- Entities｜实体

	- Group 1

		- 作品｜Work

			- e.g.: who wrote that book - a high level of abstraction, the conceptual content that underlies all of the linguistic versions, the story being told in the book, the ideas in a person's head for the book.

		- 内容表达｜Expression

			- e.g.: who translated that book - we may have a particular text in mind and a specific language.

		- 载体表现｜Manifestation

			- e.g.: a publication as when we go to a bookstore to purchase a book. we may know its ISBN but the particular copy does not matter as long as it's in good condition and not missing pages.

		- 单件｜Item

			- e.g.: to describe a physical object that has paper pages and a binding and can sometimes be used to prop open a door or hold up a table leg.

	- Group 2

	  Agents who have contributed to an instance of manga in some way
	  
		- Person
		- Corporate Body

	- Group 3

	  define things or objects which are described in or are the subject of the manga
	  
		- Concepts
		- Objects
		- Events
		- Places

### FRAD｜规范数据的功能需求

### FRSAD｜主题规范数据的功能需求

- 新增实体

	- 主题｜Thema
	- 主题表述｜Nomen

- 创建 Aboutness 模型

	- 方法 1：使用FRBR第三组实体：概念、对象、地点、事件
	- 方法 2：个人、事物、能量、空间、时间
	- 方法 3：indices 模型

		- 知觉对象
		- 概念
		- 关系

	- 方法 4：使用实际的实体列表

## 资源

### OCLC｜联机计算机图书馆中心

Online Computer Library Center

- [WorldCat](https://www.worldcat.org/)

	- APIs

		- [Classify](http://classify.oclc.org)

- [WorldShare](https://www.oclc.org/zh-Hans/worldshare.html)

### [Open Library](https://openlibrary.org)

### [CNBC｜中国国家书目中心](http://opac.nlc.cn)

中国国家书目中心已经FRBR化，但还不完善（2014-09）

### [国家图书馆外文采编部主任 顾犇](http://blog.sina.com.cn/guben)

### [数图研究笔记 刘炜 Keven](http://www.kevenlw.name/)

### [编目精灵III](http://catwizard.net)

### [rainzen](http://rainzen.bokee.com)

### [元数据标准的演变 曾蕾](http://www.jlis.cn/jtlsc/ch/reader/create_pdf.aspx?file_no=20030482)

### [FRBR对RDA的影响初探 国家图书馆 吴晓静](http://www.nlc.cn/newgtcb/gtcbywyt/bmgz/dyjwxbmgz/201106/t20110629_45615.htm)

### [https://github.com/mredar/django-dublincore](https://github.com/mredar/django-dublincore)

A Django plugin app for applying Dublin Core Metadata to any Django model.
This uses the Django contenttype framework and generic relations to apply a varying number of metadata terms to any Django model.

### [https://github.com/jermnelson/FRBR-Redis-Datastore](https://github.com/jermnelson/FRBR-Redis-Datastore)

### [https://github.com/brinxmat/Global-book-commenting](https://github.com/brinxmat/Global-book-commenting)

This software is provided as a demonstration of the concept of distributed 
FRBR-work-level book commenting, and consists of two parts: a Javascript, 
which identifies ISBNs and posts these to the second part, a web service 
in PHP which queries the OCLC xISBN web service.
The Javascript portion has two dependencies: jQuery 
<http://code.jquery.com/jquery-1.6.1.js> and 
<https://github.com/jamespadolsey/jQuery-Plugins/tree/master/cross-domain-ajax/>
To use it, just include the required libraries before the </body> tag and put 
<div id="disqus_thread"></div> somewhere in the body.

### [https://github.com/wdenton/openfrbr](https://github.com/wdenton/openfrbr)

OpenFRBR is a FRBR implementation in Ruby on Rails.  Or trying to be one.

### [https://github.com/rsinger/ruby-frbr](https://github.com/rsinger/ruby-frbr)

A very basic representation of the FRBR Group 1, 2, and 3 entities and the relationships between them.
This library is not intended to provide the actual bibliographic attributes of the entities, just establish model and the relationships.
Everything is defined as a Module that you would mixin into some other object.

A basic example:
```
# Set up our bibliographic objects that we want to FRBR-ize
class Story
  attr_accessor :title
end
class Book
  attr_accessor :language, format
end
  
class BookEdition
  attr_accessor :isbn, :date_published
end
class Person
  attr_accessor :name
end
  
story = Story.new
story.title = "The Old Man and the Sea"
story.extend(FRBR::Work) # these modules could also be included directly in the class
person = Person.new
person.name = "Ernest Hemingway"
person.extend(FRBR::Person)
story.add_creator(person) # or person.add_creation(story)
book = Book.new
book.language = 'English'
book.format = 'text'
book.extend(FRBR::Expression)
book.realization_of(story) # or story.add_realization(book)
edition = BookEdition.new
edition.isbn = '0099273969'
edition.date_published = '2000'
edition.extend(FRBR::Manifestation)
edition.embodiment_of(book) # or book.add_embodiment(edition)
```

## CIDOC CRM

CIDOC Conceptual Reference Model，用于博物馆界资源的编目

## FRBR CRM（Known as FRBRoo）

BRBRoo是CIDOC CRM与FRBR协调的产物

## PRESSoo

## MARC｜机读目录

## [MODS｜元数据对象描述标准](http://www.loc.gov/standards/mods/mods-outline-3-5.html)

## AACR｜英美编目条例

## Resource Description and Access（RDA）｜资源描述与检索

### Core Elements

- Attributes of Manifestation and Item

	- Title
	- Responsibility
	- Edition
	- Numbering of serials
	- Production

		- Date of production

	- Publication

		- Place of publication
		- Publisher's name
		- date of publication

	- Distribution

		- Place of distribution
		- Distributor's name
		- Date of distribution

	- Manufacture

		- Place of manufacture
		- Manufacturer's name
		- Date of manufacture

	- Copyright date
	- Series

		- Title of series
		- Numbering within series
		- Title of subseries
		- Numbering within subseries

	- Identifier for manifestation
	- Carrier type
	- Extend

- Attributes of Work

	- Title
	- Identifier
	- Form
	- Date
	- Place of origin
	- Other distinguishing characteristic
	- Medium of performance
	- Numeric designation of a musical work
	- Key
	- Signatory

- Atrributes of Expression

	- Identifier
	- Content type
	- Language
	- Date
	- Other distinguishing characteristic
	- Horizontal scale
	- Vertical scale

### Documents

- RDA Strategic Plan
- RDA Objectives and Principles
- RDA Scope and Structure
- Etc

