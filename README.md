docker-compass
==============

<table>
        <tr>
            <td><img width="20" src="https://cdnjs.cloudflare.com/ajax/libs/octicons/8.5.0/svg/archive.svg" alt="archived" /></td>
            <td><strong>Archived Repository</strong><br />
            This code is no longer maintained. Feel free to fork it, but use it at your own risks.
        </td>
        </tr>
</table>

Run compass within a docker container

So instead of running

    $ compass compile

You can run 

    $ docker run -ti -v `pwd`:/srv marmelab/compass compile
