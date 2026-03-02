# Server Metrics 2026-03-02 20:49:25 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.1.3

telemt_uptime_seconds 193147.0 (53h 39m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3799884
telemt_connections_bad_total 56653
telemt_handshake_timeouts_total 313072
telemt_me_keepalive_timeout_total 323
telemt_me_reconnect_attempts_total 6836
telemt_me_reconnect_success_total 6839
telemt_me_route_drop_no_conn_total 1209418
telemt_me_route_drop_channel_closed_total 23
telemt_desync_total 6794
telemt_desync_full_logged_total 2332
telemt_desync_suppressed_total 4462
telemt_desync_frames_bucket_total{bucket="1_2"} 2257
telemt_desync_frames_bucket_total{bucket="3_10"} 2245
telemt_desync_frames_bucket_total{bucket="gt_10"} 2292
telemt_pool_force_close_total 3381
telemt_pool_stale_pick_total 220454
telemt_me_writer_removed_unexpected_total 6772
telemt_me_writer_restored_same_endpoint_total 6134
telemt_me_writer_removed_unexpected_minus_restored_total 638
telemt_user_connections_total{user="hello"} 3176640
telemt_user_connections_current{user="hello"} 553
telemt_user_octets_from_client{user="hello"} 80295003636 (74.78 GB)
telemt_user_octets_to_client{user="hello"} 1196309297004 (1.09 TB)
telemt_user_unique_ips_current{user="hello"} 60
```

## server2

```
telemt 3.1.3

telemt_uptime_seconds 192921.4 (53h 35m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1716139
telemt_connections_bad_total 10237
telemt_handshake_timeouts_total 132467
telemt_me_keepalive_timeout_total 265
telemt_me_reconnect_attempts_total 7229
telemt_me_reconnect_success_total 7852
telemt_me_route_drop_no_conn_total 482582
telemt_desync_total 4200
telemt_desync_full_logged_total 1339
telemt_desync_suppressed_total 2861
telemt_desync_frames_bucket_total{bucket="1_2"} 905
telemt_desync_frames_bucket_total{bucket="3_10"} 1760
telemt_desync_frames_bucket_total{bucket="gt_10"} 1535
telemt_pool_force_close_total 3411
telemt_pool_stale_pick_total 50710
telemt_me_writer_removed_unexpected_total 7614
telemt_me_writer_restored_same_endpoint_total 6720
telemt_me_writer_removed_unexpected_minus_restored_total 894
telemt_user_connections_total{user="hello"} 1330946
telemt_user_connections_current{user="hello"} 322
telemt_user_octets_from_client{user="hello"} 30313810884 (28.23 GB)
telemt_user_octets_to_client{user="hello"} 574364735560 (534.92 GB)
telemt_user_unique_ips_current{user="hello"} 45
```

## server3

```
telemt 3.1.4

telemt_uptime_seconds 5811.9 (1h 36m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 48457
telemt_connections_bad_total 15
telemt_handshake_timeouts_total 458
telemt_me_keepalive_timeout_total 26
telemt_me_reconnect_attempts_total 908
telemt_me_reconnect_success_total 918
telemt_me_reader_eof_total 911
telemt_me_route_drop_no_conn_total 18267
telemt_me_route_drop_channel_closed_total 1
telemt_me_kdf_drift_total 1141
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_shadow_rotate_total 25
telemt_desync_total 186
telemt_desync_full_logged_total 80
telemt_desync_suppressed_total 106
telemt_desync_frames_bucket_total{bucket="1_2"} 65
telemt_desync_frames_bucket_total{bucket="3_10"} 60
telemt_desync_frames_bucket_total{bucket="gt_10"} 61
telemt_me_writer_removed_unexpected_total 913
telemt_me_writer_restored_same_endpoint_total 897
telemt_me_writer_removed_unexpected_minus_restored_total 16
telemt_user_connections_total{user="hello"} 44347
telemt_user_connections_current{user="hello"} 288
telemt_user_octets_from_client{user="hello"} 1814375844 (1.69 GB)
telemt_user_octets_to_client{user="hello"} 16662571420 (15.52 GB)
telemt_user_unique_ips_current{user="hello"} 36
```

## server4

```
telemt 3.1.4

telemt_uptime_seconds 5772.4 (1h 36m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 48766
telemt_connections_bad_total 15855
telemt_handshake_timeouts_total 4078
telemt_me_keepalive_timeout_total 18
telemt_me_reconnect_attempts_total 852
telemt_me_reconnect_success_total 875
telemt_me_reader_eof_total 859
telemt_me_route_drop_no_conn_total 12148
telemt_me_route_drop_channel_closed_total 1
telemt_me_kdf_drift_total 1142
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_outage_enter_total 3
telemt_me_single_endpoint_outage_exit_total 3
telemt_me_single_endpoint_outage_reconnect_attempt_total 4
telemt_me_single_endpoint_outage_reconnect_success_total 1
telemt_me_single_endpoint_quarantine_bypass_total 4
telemt_me_single_endpoint_shadow_rotate_total 25
telemt_desync_total 72
telemt_desync_full_logged_total 35
telemt_desync_suppressed_total 37
telemt_desync_frames_bucket_total{bucket="1_2"} 26
telemt_desync_frames_bucket_total{bucket="3_10"} 24
telemt_desync_frames_bucket_total{bucket="gt_10"} 22
telemt_pool_force_close_total 23
telemt_me_writer_removed_unexpected_total 860
telemt_me_writer_restored_same_endpoint_total 841
telemt_me_writer_removed_unexpected_minus_restored_total 19
telemt_user_connections_total{user="hello"} 27330
telemt_user_connections_current{user="hello"} 167
telemt_user_octets_from_client{user="hello"} 230738596 (220.05 MB)
telemt_user_octets_to_client{user="hello"} 10710036780 (9.97 GB)
telemt_user_unique_ips_current{user="hello"} 22
```

## server5

```
telemt 3.1.3

telemt_uptime_seconds 192970.7 (53h 36m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2764581
telemt_connections_bad_total 38610
telemt_handshake_timeouts_total 270668
telemt_me_keepalive_timeout_total 232
telemt_me_reconnect_attempts_total 6592
telemt_me_reconnect_success_total 7087
telemt_me_route_drop_no_conn_total 1023723
telemt_me_route_drop_channel_closed_total 44
telemt_desync_total 4519
telemt_desync_full_logged_total 1300
telemt_desync_suppressed_total 3219
telemt_desync_frames_bucket_total{bucket="1_2"} 1240
telemt_desync_frames_bucket_total{bucket="3_10"} 1807
telemt_desync_frames_bucket_total{bucket="gt_10"} 1472
telemt_pool_force_close_total 3487
telemt_pool_stale_pick_total 114652
telemt_me_writer_removed_unexpected_total 6930
telemt_me_writer_restored_same_endpoint_total 6193
telemt_me_writer_removed_unexpected_minus_restored_total 737
telemt_user_connections_total{user="hello"} 2306516
telemt_user_connections_current{user="hello"} 338
telemt_user_octets_from_client{user="hello"} 35640599508 (33.19 GB)
telemt_user_octets_to_client{user="hello"} 813159229616 (757.31 GB)
telemt_user_unique_ips_current{user="hello"} 45
```