````Csharp    

using Microsoft.EntityFrameworkCore;
using StudentApplication.Models.Entities;

namespace StudentApplication.Models
{
    public class MyDbContext : DbContext
    {
        public DbSet<Student> Students { get; set; }

        protected override void OnConfiguring(DbContextOptionsBuilder optionBuilder)
        {
            optionBuilder.UseSqlite("Filename=./mydb.db");
        } 
    }

}


````

