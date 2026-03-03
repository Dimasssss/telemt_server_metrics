# Server Metrics 2026-03-03 19:34:24 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.1.5

telemt_uptime_seconds 47549.6 (13h 12m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1239175
telemt_connections_bad_total 9819
telemt_handshake_timeouts_total 12857
telemt_me_keepalive_timeout_total 93
telemt_me_reconnect_attempts_total 4038
telemt_me_reconnect_success_total 4018
telemt_me_reader_eof_total 4034
telemt_me_route_drop_no_conn_total 461153
telemt_me_route_drop_channel_closed_total 4
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_single_endpoint_outage_enter_total 3
telemt_me_single_endpoint_outage_exit_total 3
telemt_me_single_endpoint_outage_reconnect_attempt_total 3
telemt_me_single_endpoint_quarantine_bypass_total 3
telemt_me_single_endpoint_shadow_rotate_total 190
telemt_me_floor_mode{mode="static"} 1
telemt_desync_total 2999
telemt_desync_full_logged_total 959
telemt_desync_suppressed_total 2040
telemt_desync_frames_bucket_total{bucket="1_2"} 826
telemt_desync_frames_bucket_total{bucket="3_10"} 1003
telemt_desync_frames_bucket_total{bucket="gt_10"} 1170
telemt_pool_swap_total 13
telemt_pool_force_close_total 722
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 4036
telemt_me_writer_restored_same_endpoint_total 3981
telemt_me_writer_removed_unexpected_minus_restored_total 55
telemt_user_connections_total{user="hello"} 1018604
telemt_user_connections_current{user="hello"} 911
telemt_user_octets_from_client{user="hello"} 16855879380 (15.70 GB)
telemt_user_octets_to_client{user="hello"} 389893524540 (363.12 GB)
telemt_user_unique_ips_current{user="hello"} 106
```

## server2

```
telemt 3.1.5

telemt_uptime_seconds 47546.6 (13h 12m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 557404
telemt_connections_bad_total 5284
telemt_handshake_timeouts_total 34005
telemt_me_keepalive_timeout_total 422
telemt_me_reconnect_attempts_total 3651
telemt_me_reconnect_success_total 3647
telemt_me_reader_eof_total 3642
telemt_me_seq_mismatch_total 9
telemt_me_route_drop_no_conn_total 256764
telemt_me_endpoint_quarantine_total 9
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_single_endpoint_outage_enter_total 5
telemt_me_single_endpoint_outage_exit_total 5
telemt_me_single_endpoint_outage_reconnect_attempt_total 6
telemt_me_single_endpoint_outage_reconnect_success_total 1
telemt_me_single_endpoint_quarantine_bypass_total 6
telemt_me_single_endpoint_shadow_rotate_total 194
telemt_me_floor_mode{mode="static"} 1
telemt_desync_total 616
telemt_desync_full_logged_total 189
telemt_desync_suppressed_total 427
telemt_desync_frames_bucket_total{bucket="1_2"} 140
telemt_desync_frames_bucket_total{bucket="3_10"} 242
telemt_desync_frames_bucket_total{bucket="gt_10"} 234
telemt_pool_swap_total 17
telemt_pool_force_close_total 665
telemt_pool_stale_pick_total 318
telemt_me_writer_removed_unexpected_total 3715
telemt_me_writer_restored_same_endpoint_total 3592
telemt_me_writer_restored_fallback_total 9
telemt_me_writer_removed_unexpected_minus_restored_total 114
telemt_user_connections_total{user="hello"} 503895
telemt_user_connections_current{user="hello"} 486
telemt_user_octets_from_client{user="hello"} 8262882236 (7.70 GB)
telemt_user_octets_to_client{user="hello"} 190152190004 (177.09 GB)
telemt_user_unique_ips_current{user="hello"} 48
```

## server3

```
telemt 3.1.5

telemt_uptime_seconds 47546.9 (13h 12m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 662081
telemt_connections_bad_total 15887
telemt_handshake_timeouts_total 46880
telemt_me_keepalive_timeout_total 116
telemt_me_reconnect_attempts_total 5492
telemt_me_reconnect_success_total 5485
telemt_me_reader_eof_total 5521
telemt_me_route_drop_no_conn_total 233811
telemt_me_route_drop_channel_closed_total 16
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_single_endpoint_outage_enter_total 4
telemt_me_single_endpoint_outage_exit_total 4
telemt_me_single_endpoint_outage_reconnect_attempt_total 5
telemt_me_single_endpoint_quarantine_bypass_total 5
telemt_me_single_endpoint_shadow_rotate_total 191
telemt_me_floor_mode{mode="static"} 1
telemt_desync_total 2054
telemt_desync_full_logged_total 633
telemt_desync_suppressed_total 1421
telemt_desync_frames_bucket_total{bucket="1_2"} 581
telemt_desync_frames_bucket_total{bucket="3_10"} 696
telemt_desync_frames_bucket_total{bucket="gt_10"} 777
telemt_pool_swap_total 16
telemt_pool_force_close_total 515
telemt_pool_stale_pick_total 249
telemt_me_writer_removed_unexpected_total 5524
telemt_me_writer_restored_same_endpoint_total 5445
telemt_me_writer_removed_unexpected_minus_restored_total 79
telemt_user_connections_total{user="hello"} 560276
telemt_user_connections_current{user="hello"} 341
telemt_user_octets_from_client{user="hello"} 7168890436 (6.68 GB)
telemt_user_octets_to_client{user="hello"} 212440196036 (197.85 GB)
telemt_user_unique_ips_current{user="hello"} 26
```

## server4

```
telemt 3.1.5

telemt_uptime_seconds 195.1 (0h 3m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 79
telemt_connections_bad_total 1
telemt_handshake_timeouts_total 2
telemt_me_reconnect_attempts_total 35
telemt_me_reconnect_success_total 62
telemt_me_reader_eof_total 42
telemt_me_route_drop_no_conn_total 5
telemt_me_single_endpoint_shadow_rotate_total 4
telemt_me_floor_mode{mode="static"} 1
telemt_me_writer_removed_unexpected_total 42
telemt_me_writer_restored_same_endpoint_total 35
telemt_me_writer_removed_unexpected_minus_restored_total 7
telemt_user_connections_total{user="hello"} 76
telemt_user_connections_current{user="hello"} 25
telemt_user_octets_from_client{user="hello"} 346784 (338.66 KB)
telemt_user_octets_to_client{user="hello"} 14996460 (14.30 MB)
telemt_user_unique_ips_current{user="hello"} 6
```

## server5

```
telemt 3.1.5

telemt_uptime_seconds 45099.5 (12h 31m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 719775
telemt_connections_bad_total 7229
telemt_handshake_timeouts_total 160684
telemt_me_keepalive_timeout_total 187
telemt_me_reconnect_attempts_total 7478
telemt_me_reconnect_success_total 7452
telemt_me_reader_eof_total 7513
telemt_me_route_drop_no_conn_total 303674
telemt_me_route_drop_channel_closed_total 6
telemt_me_hardswap_pending_ttl_expired_total 10
telemt_me_single_endpoint_outage_enter_total 5
telemt_me_single_endpoint_outage_exit_total 5
telemt_me_single_endpoint_outage_reconnect_attempt_total 5
telemt_me_single_endpoint_outage_reconnect_success_total 1
telemt_me_single_endpoint_quarantine_bypass_total 5
telemt_me_single_endpoint_shadow_rotate_total 176
telemt_me_floor_mode{mode="static"} 1
telemt_desync_total 719
telemt_desync_full_logged_total 274
telemt_desync_suppressed_total 445
telemt_desync_frames_bucket_total{bucket="1_2"} 145
telemt_desync_frames_bucket_total{bucket="3_10"} 294
telemt_desync_frames_bucket_total{bucket="gt_10"} 280
telemt_pool_swap_total 10
telemt_pool_force_close_total 433
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 7518
telemt_me_writer_restored_same_endpoint_total 7415
telemt_me_writer_removed_unexpected_minus_restored_total 103
telemt_user_connections_total{user="hello"} 532256
telemt_user_connections_current{user="hello"} 399
telemt_user_octets_from_client{user="hello"} 8339064876 (7.77 GB)
telemt_user_octets_to_client{user="hello"} 180291764764 (167.91 GB)
telemt_user_connections_total{user="hello2"} 6
telemt_user_octets_from_client{user="hello2"} 4260 (4.16 KB)
telemt_user_octets_to_client{user="hello2"} 5848 (5.71 KB)
telemt_user_unique_ips_current{user="hello"} 31
```