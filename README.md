# Workshop5-assignment

გამოიყენეთ მეოთხე დავალებაში მოცემული ფორმები და გამოიყენეთ ჩემს მიერ მოწოდებული API,რომ გააგზავნოთ შემდეგი რექუესტები:
github link: https://github.com/demna-miqava/workshop6-api
Მომხმარებლების ლისტის წამოღება: http://localhost:3001/users
მომხმარებლის დამატება: http://localhost:3001/users PAYLOAD: {firstName, lastName, email, age}
Მომხმარებლის განახლება:  http://localhost:3001/users/${userId} PAYLOAD: {firstName, lastName, email, age}
Მომხმარებლის წაშლა:  http://localhost:3001/users/${userId}
თითოეული რექუესტის დაწყებისას უნდა დაისეტოს loading სტეიტი და გამოჩნდეს ეკრანზე სპინერი, დასრულებისას კი გაქრეს.
მოხმარებლის დამატების,განახლების ან წაშლის რექუესტების დასრულების შემდეგ მაშინვე უნდა წამოვიღოთ მომხმარებლების განახლებული სია და გამოვაჩინოთ ეკრანზე.
