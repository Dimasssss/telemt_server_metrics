# Server Metrics 2026-03-06 23:38:29 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.5

telemt_uptime_seconds 19824.0 (5h 30m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 280732
telemt_connections_bad_total 3003
telemt_handshake_timeouts_total 9271
telemt_upstream_connect_attempt_total 46455
telemt_upstream_connect_success_total 45443
telemt_upstream_connect_fail_total 875
telemt_upstream_connect_attempts_per_request{bucket="1"} 46318
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 15911
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 29307
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 84
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 141
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 875
telemt_me_keepalive_timeout_total 1381
telemt_me_reconnect_attempts_total 22334
telemt_me_reconnect_success_total 21503
telemt_me_reader_eof_total 24665
telemt_me_idle_close_by_peer_total 24665
telemt_me_route_drop_no_conn_total 110217
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_single_endpoint_shadow_rotate_total 160
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 940
telemt_desync_full_logged_total 259
telemt_desync_suppressed_total 681
telemt_desync_frames_bucket_total{bucket="1_2"} 263
telemt_desync_frames_bucket_total{bucket="3_10"} 403
telemt_desync_frames_bucket_total{bucket="gt_10"} 274
telemt_pool_swap_total 6
telemt_pool_force_close_total 379
telemt_pool_stale_pick_total 176
telemt_me_writer_removed_unexpected_total 24776
telemt_me_writer_restored_same_endpoint_total 21449
telemt_me_writer_restored_fallback_total 48
telemt_me_async_recovery_trigger_total 14985
telemt_me_writer_removed_unexpected_minus_restored_total 3279
telemt_user_connections_total{user="hello"} 253994
telemt_user_connections_current{user="hello"} 340
telemt_user_octets_from_client{user="hello"} 4022283768 (3.75 GB)
telemt_user_octets_to_client{user="hello"} 114921572220 (107.03 GB)
telemt_user_unique_ips_current{user="hello"} 115
telemt_user_unique_ips_recent_window{user="hello"} 36
```

## server2

```
telemt 3.3.5

telemt_uptime_seconds 19824.0 (5h 30m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 117196
telemt_connections_bad_total 101
telemt_handshake_timeouts_total 12100
telemt_upstream_connect_attempt_total 75265
telemt_upstream_connect_success_total 75263
telemt_upstream_connect_attempts_per_request{bucket="1"} 75263
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 46830
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 28403
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 30
telemt_me_keepalive_timeout_total 867
telemt_me_reconnect_attempts_total 48390
telemt_me_reconnect_success_total 48198
telemt_me_reader_eof_total 47507
telemt_me_idle_close_by_peer_total 47503
telemt_me_route_drop_no_conn_total 39812
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_single_endpoint_shadow_rotate_total 168
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 782
telemt_desync_full_logged_total 205
telemt_desync_suppressed_total 577
telemt_desync_frames_bucket_total{bucket="1_2"} 131
telemt_desync_frames_bucket_total{bucket="3_10"} 390
telemt_desync_frames_bucket_total{bucket="gt_10"} 261
telemt_pool_swap_total 11
telemt_pool_force_close_total 604
telemt_pool_stale_pick_total 55
telemt_me_writer_removed_unexpected_total 47531
telemt_me_writer_restored_same_endpoint_total 48196
telemt_me_async_recovery_trigger_total 14979
telemt_user_connections_total{user="hello"} 99095
telemt_user_connections_current{user="hello"} 175
telemt_user_octets_from_client{user="hello"} 1484378576 (1.38 GB)
telemt_user_octets_to_client{user="hello"} 35926566904 (33.46 GB)
telemt_user_unique_ips_current{user="hello"} 56
telemt_user_unique_ips_recent_window{user="hello"} 17
```

## server3

```
telemt 3.3.5

telemt_uptime_seconds 19824.0 (5h 30m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 216576
telemt_connections_bad_total 1092
telemt_handshake_timeouts_total 3521
telemt_upstream_connect_attempt_total 57993
telemt_upstream_connect_success_total 57833
telemt_upstream_connect_fail_total 52
telemt_upstream_connect_attempts_per_request{bucket="1"} 57885
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 33733
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 23943
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 156
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 52
telemt_me_keepalive_timeout_total 1590
telemt_me_reconnect_attempts_total 34786
telemt_me_reconnect_success_total 34737
telemt_me_reader_eof_total 35915
telemt_me_idle_close_by_peer_total 35912
telemt_me_route_drop_no_conn_total 82419
telemt_me_route_drop_channel_closed_total 1
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_shadow_rotate_total 162
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 991
telemt_desync_full_logged_total 250
telemt_desync_suppressed_total 741
telemt_desync_frames_bucket_total{bucket="1_2"} 185
telemt_desync_frames_bucket_total{bucket="3_10"} 395
telemt_desync_frames_bucket_total{bucket="gt_10"} 411
telemt_pool_swap_total 11
telemt_pool_force_close_total 316
telemt_pool_stale_pick_total 116
telemt_me_writer_removed_unexpected_total 36073
telemt_me_writer_restored_same_endpoint_total 34730
telemt_me_async_recovery_trigger_total 44787
telemt_me_writer_removed_unexpected_minus_restored_total 1343
telemt_user_connections_total{user="hello"} 201328
telemt_user_connections_current{user="hello"} 143
telemt_user_octets_from_client{user="hello"} 15923564196 (14.83 GB)
telemt_user_octets_to_client{user="hello"} 59253787056 (55.18 GB)
telemt_user_unique_ips_current{user="hello"} 71
telemt_user_unique_ips_recent_window{user="hello"} 20
```

## server4

```
telemt 3.3.5

telemt_uptime_seconds 19824.5 (5h 30m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 216680
telemt_connections_bad_total 57784
telemt_handshake_timeouts_total 16168
telemt_upstream_connect_attempt_total 34477
telemt_upstream_connect_success_total 34397
telemt_upstream_connect_fail_total 33
telemt_upstream_connect_attempts_per_request{bucket="1"} 34430
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14240
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 20124
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 33
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 33
telemt_me_keepalive_timeout_total 681
telemt_me_reconnect_attempts_total 11070
telemt_me_reconnect_success_total 11047
telemt_me_reader_eof_total 14978
telemt_me_idle_close_by_peer_total 14976
telemt_me_route_drop_no_conn_total 58623
telemt_me_single_endpoint_shadow_rotate_total 163
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 199
telemt_desync_full_logged_total 84
telemt_desync_suppressed_total 115
telemt_desync_frames_bucket_total{bucket="1_2"} 69
telemt_desync_frames_bucket_total{bucket="3_10"} 75
telemt_desync_frames_bucket_total{bucket="gt_10"} 55
telemt_pool_swap_total 10
telemt_pool_force_close_total 368
telemt_pool_stale_pick_total 450
telemt_me_writer_removed_unexpected_total 14983
telemt_me_writer_restored_same_endpoint_total 11042
telemt_me_writer_removed_unexpected_minus_restored_total 3941
telemt_user_connections_total{user="hello"} 139015
telemt_user_connections_current{user="hello"} 123
telemt_user_octets_from_client{user="hello"} 1661711572 (1.55 GB)
telemt_user_octets_to_client{user="hello"} 45529037796 (42.40 GB)
telemt_user_unique_ips_current{user="hello"} 53
telemt_user_unique_ips_recent_window{user="hello"} 17
```

## server5

```
telemt 3.3.5

telemt_uptime_seconds 19822.7 (5h 30m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 188887
telemt_connections_bad_total 494
telemt_handshake_timeouts_total 1835
telemt_upstream_connect_attempt_total 31017
telemt_upstream_connect_success_total 30875
telemt_upstream_connect_fail_total 19
telemt_upstream_connect_attempts_per_request{bucket="1"} 30894
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12390
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 18268
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 9
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 208
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 19
telemt_me_keepalive_timeout_total 958
telemt_me_reconnect_attempts_total 8965
telemt_me_reconnect_success_total 8934
telemt_me_reader_eof_total 12056
telemt_me_idle_close_by_peer_total 12055
telemt_me_route_drop_no_conn_total 63869
telemt_me_route_drop_channel_closed_total 4
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_shadow_rotate_total 159
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 755
telemt_desync_full_logged_total 191
telemt_desync_suppressed_total 564
telemt_desync_frames_bucket_total{bucket="1_2"} 263
telemt_desync_frames_bucket_total{bucket="3_10"} 245
telemt_desync_frames_bucket_total{bucket="gt_10"} 247
telemt_pool_swap_total 11
telemt_pool_force_close_total 365
telemt_pool_stale_pick_total 215
telemt_me_writer_removed_unexpected_total 12123
telemt_me_writer_restored_same_endpoint_total 8930
telemt_me_writer_removed_unexpected_minus_restored_total 3193
telemt_user_connections_total{user="hello"} 173054
telemt_user_connections_current{user="hello"} 184
telemt_user_octets_from_client{user="hello"} 10060836628 (9.37 GB)
telemt_user_octets_to_client{user="hello"} 59622933820 (55.53 GB)
telemt_user_unique_ips_current{user="hello"} 62
telemt_user_unique_ips_recent_window{user="hello"} 22
```