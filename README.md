# terminal-table-project_sbrycbc

Das project Terminal Table

# Usage
Import and initialize a new table.

        const table = new Table();
        
- create an array for your tables columns, including the key, to connect the rows to, the title of the column and the width of the column.

        const columns =
      [
       {
        key: 'id',
        title: '#',
        width: 10
       },
       
       {
        key: 'name',
        title: 'Name',
        width: 25
       },
       
       {
        key: 'group',
        title: 'Group',
        width: 15
        },
        
        {
        key: 'role',
        title: 'Role',
        width: 50
        }
       ]
        
        
- Create an array for the rows, including all columns as keys.

        const rows =
      [
         {
        id: 1,
        name: 'Thingy 1',
        group: 'this',
        role: 'Admin'
          },
          
         {
        id: 2,
        name: 'Thingy 2',
        group: 'other',
        role: 'Admin'
          },
          
         {
        id: 3,
        name: 'Thingy 3',
        group: 'this',
        role: 'Moderator'
          }
      ];
