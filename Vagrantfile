Vagrant.configure("2") do |config|
 
  config.vm.box = "ubuntu/xenial64"
  config.vm.hostname = "miguel-fernandez-valles"

  config.vm.provision "shell", inline: <<-SHELL

  ##generar archivo SQL con los registros de empleados
  echo " -- Insertar datos en my SQL
  'libros'" > /home/vagrante/datos_libros.sql
  echo "
  INSERT INTO gestion_librelia.libros (titulo,
  autor, anio_publicacion, genero, precio) VALUES" >> /home/vagrant/datos_libros.sql
  echo "('Cien Años de Soledad', 'Gabriel GArcía Marcos', '1605', 'Novela', '12,99')" >> /home/vagrant/datos_libros.sql
  SHELL
  
end
