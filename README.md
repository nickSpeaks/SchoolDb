# SchoolDb

# ========================================
# Online Store Basic Data Model 

 Main Entities:

-Customer: Represents users of the store, storing information 
  like name, email (unique), and potentially other details. <br>
-Product: Represents items for sale, including name, description, 
  price, stock level, and other relevant attributes.  <br>
-CustomerOrder: Represents a customer's purchase, containing 
  the order date, customer reference, and potentially additional order information.<br>
-OrderItem: Links a specific customer order with the 
purchased products and their quantities.<br>

Relationships:

-A customer can place multiple orders (one-to-many).<br>
-An order contains multiple order items (one-to-many).<br>
-Each order item is associated with a specific product 
 and a specific customer order.<br>
-Foreign keys enforce data integrity by ensuring 
 references to existing records in related tables.<br>

 # =======================================
 # Trading Stock Data Model

 # Many-to-Many:<br> 
  The Transaction table clearly shows the many-to-many  <br> 
  relationship between traders and stocks. A single trader can have <br>
  many transactions, and a single stock can be involved in many <br>
  transactions with different traders. The foreign keys enforce <br>
  this by ensuring each transaction references a valid trader and stock <br>


 
