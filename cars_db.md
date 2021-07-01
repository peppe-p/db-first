# Cars DB

**id**              BIGINT          NOTNULL     AUTO_INCREMENT  UNIQUE
**model**           VARCHAR(30)     NOTNULL     
**brand**           VARCHAR(30)     NOTNULL     
**km_traveled**     MEDIUMINT       NOTNULL     
**price**           INT             NOTNULL     
**horse_p**         SMALLINT        NOTNULL     
**fuel_type**       VARCHAR(20)     NULL        
**color**           VARCHAR(15)     NOTNULL     
**wrapped**         TINYINT(2)      DEFAULT(0)  
**note**            TEXT            NULL        
