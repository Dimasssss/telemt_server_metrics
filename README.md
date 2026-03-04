# Server Metrics 2026-03-04 04:01:24 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.1.6

telemt_uptime_seconds 24646.2 (6h 50m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 161217
telemt_connections_bad_total 1617
telemt_handshake_timeouts_total 2899
telemt_upstream_connect_attempt_total 18272
telemt_upstream_connect_success_total 18197
telemt_upstream_connect_fail_total 33
telemt_upstream_connect_attempts_per_request{bucket="1"} 18197
telemt_upstream_connect_attempts_per_request{bucket="2"} 33
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10251
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7923
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 9
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 14
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 33
telemt_me_keepalive_timeout_total 197
telemt_me_reconnect_attempts_total 4285
telemt_me_reconnect_success_total 4271
telemt_me_reader_eof_total 4372
telemt_me_idle_close_by_peer_total 4372
telemt_me_route_drop_no_conn_total 53969
telemt_me_route_drop_channel_closed_total 1
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_single_endpoint_shadow_rotate_total 102
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 385
telemt_desync_full_logged_total 138
telemt_desync_suppressed_total 247
telemt_desync_frames_bucket_total{bucket="1_2"} 102
telemt_desync_frames_bucket_total{bucket="3_10"} 137
telemt_desync_frames_bucket_total{bucket="gt_10"} 146
telemt_pool_swap_total 5
telemt_pool_force_close_total 168
telemt_me_writer_removed_unexpected_total 4372
telemt_me_writer_restored_same_endpoint_total 4251
telemt_me_writer_removed_unexpected_minus_restored_total 121
telemt_user_connections_total{user="hello"} 153147
telemt_user_connections_current{user="hello"} 540
telemt_user_octets_from_client{user="hello"} 1499404944 (1.40 GB)
telemt_user_octets_to_client{user="hello"} 47392653592 (44.14 GB)
telemt_user_unique_ips_current{user="hello"} 88
```

## server2

```
telemt 3.1.6

telemt_uptime_seconds 24642.7 (6h 50m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 76343
telemt_connections_bad_total 292
telemt_handshake_timeouts_total 19969
telemt_upstream_connect_attempt_total 60790
telemt_upstream_connect_success_total 60179
telemt_upstream_connect_fail_total 289
telemt_upstream_connect_attempts_per_request{bucket="1"} 60173
telemt_upstream_connect_attempts_per_request{bucket="2"} 295
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 41117
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 19042
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 20
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 289
telemt_me_keepalive_timeout_total 944
telemt_me_reconnect_attempts_total 38382
telemt_me_reconnect_success_total 38357
telemt_me_reader_eof_total 39331
telemt_me_idle_close_by_peer_total 39330
telemt_me_route_drop_no_conn_total 23938
telemt_me_hardswap_pending_ttl_expired_total 8
telemt_me_single_endpoint_shadow_rotate_total 108
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 187
telemt_desync_full_logged_total 76
telemt_desync_suppressed_total 111
telemt_desync_frames_bucket_total{bucket="1_2"} 41
telemt_desync_frames_bucket_total{bucket="3_10"} 100
telemt_desync_frames_bucket_total{bucket="gt_10"} 46
telemt_pool_swap_total 1
telemt_pool_force_close_total 75
telemt_me_writer_removed_unexpected_total 39392
telemt_me_writer_restored_same_endpoint_total 38336
telemt_me_writer_removed_unexpected_minus_restored_total 1056
telemt_user_connections_total{user="hello"} 55176
telemt_user_connections_current{user="hello"} 180
telemt_user_octets_from_client{user="hello"} 453553496 (432.54 MB)
telemt_user_octets_to_client{user="hello"} 26841727120 (25.00 GB)
telemt_user_unique_ips_current{user="hello"} 30
```

## server3

```
telemt 3.1.6

telemt_uptime_seconds 24641.5 (6h 50m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 173015
telemt_connections_bad_total 62860
telemt_handshake_timeouts_total 4114
telemt_upstream_connect_attempt_total 33268
telemt_upstream_connect_success_total 33049
telemt_upstream_connect_fail_total 102
telemt_upstream_connect_attempts_per_request{bucket="1"} 33049
telemt_upstream_connect_attempts_per_request{bucket="2"} 102
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 19424
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13522
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 103
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 102
telemt_me_keepalive_timeout_total 442
telemt_me_reconnect_attempts_total 13841
telemt_me_reconnect_success_total 13809
telemt_me_reader_eof_total 14544
telemt_me_idle_close_by_peer_total 14541
telemt_me_route_drop_no_conn_total 33841
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_single_endpoint_shadow_rotate_total 106
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 300
telemt_desync_full_logged_total 106
telemt_desync_suppressed_total 194
telemt_desync_frames_bucket_total{bucket="1_2"} 63
telemt_desync_frames_bucket_total{bucket="3_10"} 109
telemt_desync_frames_bucket_total{bucket="gt_10"} 128
telemt_pool_swap_total 3
telemt_pool_force_close_total 113
telemt_me_writer_removed_unexpected_total 14549
telemt_me_writer_restored_same_endpoint_total 13788
telemt_me_writer_removed_unexpected_minus_restored_total 761
telemt_user_connections_total{user="hello"} 102458
telemt_user_connections_current{user="hello"} 217
telemt_user_octets_from_client{user="hello"} 635487636 (606.05 MB)
telemt_user_octets_to_client{user="hello"} 27066526160 (25.21 GB)
telemt_user_unique_ips_current{user="hello"} 29
```

## server4

```
telemt 3.1.6

telemt_uptime_seconds 24640.5 (6h 50m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 84809
telemt_connections_bad_total 2990
telemt_handshake_timeouts_total 842
telemt_upstream_connect_attempt_total 16540
telemt_upstream_connect_success_total 16463
telemt_upstream_connect_fail_total 38
telemt_upstream_connect_attempts_per_request{bucket="1"} 16463
telemt_upstream_connect_attempts_per_request{bucket="2"} 38
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10109
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6353
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 38
telemt_me_keepalive_timeout_total 177
telemt_me_reconnect_attempts_total 2452
telemt_me_reconnect_success_total 2454
telemt_me_reader_eof_total 2472
telemt_me_idle_close_by_peer_total 2472
telemt_me_route_drop_no_conn_total 27916
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_single_endpoint_shadow_rotate_total 105
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 98
telemt_desync_full_logged_total 37
telemt_desync_suppressed_total 61
telemt_desync_frames_bucket_total{bucket="1_2"} 22
telemt_desync_frames_bucket_total{bucket="3_10"} 56
telemt_desync_frames_bucket_total{bucket="gt_10"} 20
telemt_pool_swap_total 7
telemt_pool_force_close_total 157
telemt_me_writer_removed_unexpected_total 2472
telemt_me_writer_restored_same_endpoint_total 2433
telemt_me_writer_removed_unexpected_minus_restored_total 39
telemt_user_connections_total{user="hello"} 77622
telemt_user_connections_current{user="hello"} 188
telemt_user_octets_from_client{user="hello"} 675972160 (644.66 MB)
telemt_user_octets_to_client{user="hello"} 26588481524 (24.76 GB)
telemt_user_unique_ips_current{user="hello"} 27
```

## server5

```
telemt 3.1.6

telemt_uptime_seconds 24639.1 (6h 50m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 190567
telemt_connections_bad_total 1675
telemt_handshake_timeouts_total 87632
telemt_upstream_connect_attempt_total 37119
telemt_upstream_connect_success_total 36872
telemt_upstream_connect_fail_total 115
telemt_upstream_connect_attempts_per_request{bucket="1"} 36872
telemt_upstream_connect_attempts_per_request{bucket="2"} 115
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 21601
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15177
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 92
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 115
telemt_me_keepalive_timeout_total 517
telemt_me_reconnect_attempts_total 18628
telemt_me_reconnect_success_total 18620
telemt_me_reader_eof_total 19718
telemt_me_idle_close_by_peer_total 19717
telemt_me_route_drop_no_conn_total 47373
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_single_endpoint_shadow_rotate_total 105
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 129
telemt_desync_full_logged_total 33
telemt_desync_suppressed_total 96
telemt_desync_frames_bucket_total{bucket="1_2"} 21
telemt_desync_frames_bucket_total{bucket="3_10"} 62
telemt_desync_frames_bucket_total{bucket="gt_10"} 46
telemt_pool_swap_total 3
telemt_pool_force_close_total 85
telemt_pool_stale_pick_total 2751
telemt_me_writer_removed_unexpected_total 19729
telemt_me_writer_restored_same_endpoint_total 18596
telemt_me_writer_removed_unexpected_minus_restored_total 1133
telemt_user_connections_total{user="hello"} 97742
telemt_user_connections_current{user="hello"} 180
telemt_user_octets_from_client{user="hello"} 617901296 (589.28 MB)
telemt_user_octets_to_client{user="hello"} 22259454496 (20.73 GB)
telemt_user_unique_ips_current{user="hello"} 23
```