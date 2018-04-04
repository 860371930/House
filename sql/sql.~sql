create table USERS
(
  ID        NUMBER not null,
  NAME      VARCHAR2(50),
  PASSWORD  VARCHAR2(50),
  TELEPHONE VARCHAR2(15),
  USERNAME  VARCHAR2(50),
  ISADMIN   VARCHAR2(5)
);
create table DISTRICT
(
  ID   NUMBER not null,
  NAME VARCHAR2(50) not null
);
create table HOUSE
(
  ID          NUMBER,
  USER_ID     NUMBER,
  TYPE_ID     NUMBER,
  TITLE       NVARCHAR2(50),
  DESCRIPTION NVARCHAR2(2000),
  PRICE       NUMBER,
  PUBDATE     DATE,
  FLOORAGE    NUMBER,
  CONTACT     VARCHAR2(100),
  STREET_ID   NUMBER
);
create table STREET
(
  ID          NUMBER not null,
  NAME        VARCHAR2(50),
  DISTRICT_ID NUMBER
);
create table TYPE
(
  ID   NUMBER not null,
  NAME VARCHAR2(10) not null
)；

insert into DISTRICT (ID, NAME)
values (1001, '东城');
insert into DISTRICT (ID, NAME)
values (1002, '西城');
insert into DISTRICT (ID, NAME)
values (1003, '石景山');
insert into DISTRICT (ID, NAME)
values (1006, '朝阳');
insert into DISTRICT (ID, NAME)
values (1000, '丰台');
insert into DISTRICT (ID, NAME)
values (1004, '海淀');

select * from DISTRICT


insert into STREET (ID, NAME, DISTRICT_ID)
values (1000, '知春路', 1004);
insert into STREET (ID, NAME, DISTRICT_ID)
values (1001, '中关村大街', 1004);
insert into STREET (ID, NAME, DISTRICT_ID)
values (1002, '学院路', 1004);
insert into STREET (ID, NAME, DISTRICT_ID)
values (1003, '朝阳路', 1006);

select * from street

insert into TYPE (ID, NAME)
values (1000, '一室一厅');
insert into TYPE (ID, NAME)
values (1001, '一室两厅');
insert into TYPE (ID, NAME)
values (1002, '两室一厅');
insert into TYPE (ID, NAME)
values (1003, '两室两厅');
insert into TYPE (ID, NAME)
values (1004, '三室一厅');
insert into TYPE (ID, NAME)
values (1005, '三室两厅');
insert into TYPE (ID, NAME)
values (1006, '四室一厅');
insert into TYPE (ID, NAME)
values (1007, '四室两厅');
insert into TYPE (ID, NAME)
values (1008, '四十三厅');

select * from type

insert into USERS (ID, NAME,PASSWORD,TELEPHONE,USERNAME,ISADMIN)
values (1001, 'admin','admin','18211341544','管理员',1);
insert into USERS (ID, NAME,PASSWORD,TELEPHONE,USERNAME,ISADMIN)
values (1002, 'jbit','123456','18223441214','学员',0);
insert into USERS (ID, NAME,PASSWORD,TELEPHONE,USERNAME,ISADMIN)
values (1003, 'accp','1234567','12134412147','程萌',0);
insert into USERS (ID, NAME,PASSWORD,TELEPHONE,USERNAME,ISADMIN)
values (1004, 'ACCP6','1234567','12435431814','地方',0);
insert into USERS (ID, NAME,PASSWORD,TELEPHONE,USERNAME,ISADMIN)
values (1005, 'accp5','1234567','18421238654','二次',0);

select * from users
