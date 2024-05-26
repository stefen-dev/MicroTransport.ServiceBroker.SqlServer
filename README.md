# Monitor and receive notifications on record table change

A high-level C# component used to audit, monitor and receive notifications on SQL Server's record table changes. For any record table change, as insert, update or delete operation, a notification containing values for the record changed is delivered. This notification contains insert, update or delete record values.

This table record tracking change system has the advantage to avoid a select to retrieve updated table record, because the updated table values record is delivered by notification.

## License

This project is licensed under the [MIT License](https://github.com/stefen-dev/MicroTransport.ServiceBroker.SqlServer/blob/master/LICENSE).