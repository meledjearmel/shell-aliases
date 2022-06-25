#Laravel Framework 8.81.0

#Usage:
  #command [options] [arguments]
  alias art='php artisan';

#Options:
  #-h, --help            Display help for the given command. When no command is given display help for the list command
  #-q, --quiet           Do not output any message
  #-V, --version         Display this application version
  #    --ansi|--no-ansi  Force (or disable --no-ansi) ANSI output
  #-n, --no-interaction  Do not ask any interactive question
  #    --env[=ENV]       The environment the command should run under
  #-v|vv|vvv, --verbose  Increase the verbosity of messages: 1 for normal output, 2 for more verbose output and 3 for debug

#Available commands:
  alias art:c-compiled='art clear-compiled';            #Remove the compiled class file
  alias art:completion='art completion';                #Dump the shell completion script
  alias art:db='art db';                                #Start a new database CLI session
  alias art:down='art down';                            #Put the application into maintenance / demo mode
  alias art:env='art env';                              #Display the current framework environment
  alias art:h='art help';                               #Display help for a command
  alias art:inspire='art inspire';                      #Display an inspiring quote
  alias art:list='art list';                            #List commands
  alias art:migrate='art migrate';                      #Run the database migrations
  alias art:optimize='art optimize';                    #Cache the framework bootstrap files
  alias art:serve='art serve';                          #Serve the application on the PHP development server
  alias art:do:test='art test';                            #Run the application tests
  alias art:tinker='art tinker';                        #Interact with your application
  alias art:up='art up';                                #Bring the application out of maintenance mode

 #Auth
  alias art:auth-resets='art auth:clear-resets';        #Flush expired password reset tokens

 #Cache
  #cache:clear           Flush the application cache
  #cache:forget          Remove an item from the cache
  #cache:table           Create a migration for the cache database table

 #Config
  #config:cache          Create a cache file for faster configuration loading
  #config:clear          Remove the configuration cache file

 #Database
  alias art:seed='art db:seed';                         #Seed the database with records
  alias art:wipe='art db:wipe';                         #Drop all tables, views, and types

 #Event
  #event:cache           Discover and cache the application's events and listeners
  #event:clear           Clear all cached events and listeners
  #event:generate        Generate the missing events and listeners based on registration
  #event:list            List the application's events and listeners

 #Key
  alias art:key='art key:generate';                     #Set the application key

 #Livewire
  alias livewire:s3='art livewire:configure-s3-upload-cleanup';  #Configure temporary file upload s3 directory to automatically cleanup files older than 24hrs.
  alias livewire:cp='art livewire:copy';              #Copy a Livewire component
  alias livewire:del='art livewire:delete';           #Delete a Livewire component
  alias livewire:disc='art livewire:discover';        #Regenerate Livewire component auto-discovery manifest
  alias livewire:make='art livewire:make';            #Create a new Livewire component
  alias livewire:mv='art livewire:move';              #Move a Livewire component
  alias livewire:pub='art livewire:publish';          #Publish Livewire configuration
  alias livewire:stubs='art livewire:stubs'           # Publish Livewire stubs

 #Make
  alias art:cast='art make:cast';                       #Create a new custom Eloquent cast class
  alias art:channel='art make:channel';                 #Create a new channel class
  alias art:command='art make:command';                 #Create a new Artisan command
  alias art:component='art make:component';             #Create a new view component class
  alias art:controller='art make:controller';           #Create a new controller class
  alias art:event='art make:event';                     #Create a new event class
  alias art:exception='art make:exception';             #Create a new custom exception class
  alias art:factory='art make:factory';                 #Create a new model factory
  alias art:job='art make:job';                         #Create a new job class
  alias art:listener='art make:listener';               #Create a new event listener class
  alias art:livewire='art make:livewire';               #Create a new Livewire component
  alias art:mail='art make:mail';                       #Create a new email class
  alias art:middleware='art make:middleware';           #Create a new middleware class
  alias art:migration='art make:migration';             #Create a new migration file
  alias art:model='art make:model';                     #Create a new Eloquent model class
  alias art:notify='art make:notification';             #Create a new notification class
  alias art:observer='art make:observer';               #Create a new observer class
  alias art:policy='art make:policy';                   #Create a new policy class
  alias art:provider='art make:provider';               #Create a new service provider class
  alias art:request='art make:request';                 #Create a new form request class
  alias art:resource='art make:resource';               #Create a new resource
  alias art:rule='art make:rule';                       #Create a new validation rule
  alias art:seeder='art make:seeder';                   #Create a new seeder class
  alias art:test='art make:test';                       #Create a new test class

 #Migrate
  alias art:mig:fresh='art migrate:fresh';              #Drop all tables and re-run all migrations
  alias art:mig:install='art migrate:install';          #Create the migration repository
  alias art:mig:refresh='art migrate:refresh';          #Reset and re-run all migrations
  alias art:mig:reset='art migrate:reset';              #Rollback all database migrations
  alias art:mig:back='art migrate:rollback';            #Rollback the last database migration
  alias art:mig:status='art migrate:status';            #Show the status of each migration

 #Model
  #model:prune           Prune models that are no longer needed

 #Notifications
  #notifications:table   Create a migration for the notifications table

 #Optimize
  alias art:opt='art optimize:clear';                   #Remove the cached bootstrap files

 #Package
  alias art:pkg='art package:discover';                 #Rebuild the cached package manifest

 #Queue
  #queue:batches-table   Create a migration for the batches database table
  #queue:clear           Delete all of the jobs from the specified queue
  #queue:failed          List all of the failed queue jobs
  #queue:failed-table    Create a migration for the failed queue jobs database table
  #queue:flush           Flush all of the failed queue jobs
  #queue:forget          Delete a failed queue job
  #queue:listen          Listen to a given queue
  #queue:monitor         Monitor the size of the specified queues
  #queue:prune-batches   Prune stale entries from the batches database
  #queue:prune-failed    Prune stale entries from the failed jobs table
  #queue:restart         Restart queue worker daemons after their current job
  #queue:retry           Retry a failed queue job
  #queue:retry-batch     Retry the failed jobs for a batch
  #queue:table           Create a migration for the queue jobs database table
  #queue:work            Start processing jobs on the queue as a daemon

 #Route
  alias art:r:cache='art route:cache';                  #Create a route cache file for faster route registration
  alias art:r:clear='art route:clear';                  #Remove the route cache file
  alias art:r:list='art route:list';                    #List all registered routes

 #Sail
  #sail:install          Install Laravel Sail's default Docker Compose file
  #sail:publish          Publish the Laravel Sail Docker files

 #Schedule
  #schedule:clear-cache  Delete the cached mutex files created by scheduler
  #schedule:list         List the scheduled commands
  #schedule:run          Run the scheduled commands
  #schedule:test         Run a scheduled command
  #schedule:work         Start the schedule worker

 #Schema
  alias art:schema='art schema:dump';                   #Dump the given database schema

 #session
  alias art:session='art session:table';                #Create a migration for the session database table

 #Storage
  alias art:link='art storage:link';                    #Create the symbolic links configured for the application

 #Stub
  alias art:s:publish='art stub:publish';               #Publish all stubs that are available for customization

 #Vendor
  alias art:v:publish='art vendor:publish';             #Publish any publishable assets from vendor packages

 #View
  alias art:v:cache='art view:cache';                   #Compile all of the application's Blade templates
  alias art:v:clear='art view:clear';                   #Clear all compiled view files
