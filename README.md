# Server Metrics 2026-03-05 00:17:20 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.2.1

telemt_uptime_seconds 12234.3 (3h 23m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 102477
telemt_connections_bad_total 1401
telemt_handshake_timeouts_total 754
telemt_upstream_connect_attempt_total 16529
telemt_upstream_connect_success_total 16365
telemt_upstream_connect_fail_total 51
telemt_upstream_connect_attempts_per_request{bucket="1"} 16364
telemt_upstream_connect_attempts_per_request{bucket="2"} 52
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10520
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5749
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 35
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 61
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 51
telemt_me_keepalive_timeout_total 536
telemt_me_reconnect_attempts_total 7620
telemt_me_reconnect_success_total 7613
telemt_me_reader_eof_total 7867
telemt_me_idle_close_by_peer_total 7866
telemt_me_route_drop_no_conn_total 27453
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_single_endpoint_shadow_rotate_total 55
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 134
telemt_desync_full_logged_total 80
telemt_desync_suppressed_total 54
telemt_desync_frames_bucket_total{bucket="1_2"} 56
telemt_desync_frames_bucket_total{bucket="3_10"} 69
telemt_desync_frames_bucket_total{bucket="gt_10"} 9
telemt_me_writer_removed_unexpected_total 7926
telemt_me_writer_restored_same_endpoint_total 7593
telemt_me_writer_removed_unexpected_minus_restored_total 333
telemt_user_connections_total{user="hello"} 89326
telemt_user_connections_current{user="hello"} 311
telemt_user_octets_from_client{user="hello"} 2878193692 (2.68 GB)
telemt_user_octets_to_client{user="hello"} 49219529924 (45.84 GB)
telemt_user_unique_ips_current{user="hello"} 37
```

## server2

```
telemt 3.2.1

telemt_uptime_seconds 12229.0 (3h 23m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 39887
telemt_connections_bad_total 762
telemt_handshake_timeouts_total 825
telemt_upstream_connect_attempt_total 13021
telemt_upstream_connect_success_total 12715
telemt_upstream_connect_fail_total 55
telemt_upstream_connect_attempts_per_request{bucket="1"} 12705
telemt_upstream_connect_attempts_per_request{bucket="2"} 65
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8395
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4216
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 104
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 55
telemt_me_keepalive_timeout_total 1019
telemt_me_reconnect_attempts_total 4930
telemt_me_reconnect_success_total 4904
telemt_me_reader_eof_total 4968
telemt_me_idle_close_by_peer_total 4967
telemt_me_route_drop_no_conn_total 12281
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_single_endpoint_outage_enter_total 1
telemt_me_single_endpoint_outage_exit_total 1
telemt_me_single_endpoint_outage_reconnect_attempt_total 3
telemt_me_single_endpoint_outage_reconnect_success_total 1
telemt_me_single_endpoint_quarantine_bypass_total 3
telemt_me_single_endpoint_shadow_rotate_total 55
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 138
telemt_desync_full_logged_total 53
telemt_desync_suppressed_total 85
telemt_desync_frames_bucket_total{bucket="1_2"} 40
telemt_desync_frames_bucket_total{bucket="3_10"} 50
telemt_desync_frames_bucket_total{bucket="gt_10"} 48
telemt_pool_swap_total 1
telemt_pool_force_close_total 34
telemt_me_writer_removed_unexpected_total 5072
telemt_me_writer_restored_same_endpoint_total 4879
telemt_me_writer_removed_unexpected_minus_restored_total 193
telemt_user_connections_total{user="hello"} 36111
telemt_user_connections_current{user="hello"} 76
telemt_user_octets_from_client{user="hello"} 313453220 (298.93 MB)
telemt_user_octets_to_client{user="hello"} 10224479044 (9.52 GB)
telemt_user_unique_ips_current{user="hello"} 14
```

## server3

```
telemt 3.2.1

telemt_uptime_seconds 12225.7 (3h 23m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 92816
telemt_connections_bad_total 1310
telemt_handshake_timeouts_total 689
telemt_upstream_connect_attempt_total 5220
telemt_upstream_connect_success_total 5166
telemt_upstream_connect_fail_total 19
telemt_upstream_connect_attempts_per_request{bucket="1"} 5166
telemt_upstream_connect_attempts_per_request{bucket="2"} 19
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2688
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2452
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 26
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 19
telemt_me_keepalive_timeout_total 51
telemt_me_reconnect_attempts_total 262
telemt_me_reconnect_success_total 272
telemt_me_reader_eof_total 261
telemt_me_idle_close_by_peer_total 261
telemt_me_route_drop_no_conn_total 26571
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_shadow_rotate_total 51
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 172
telemt_desync_full_logged_total 52
telemt_desync_suppressed_total 120
telemt_desync_frames_bucket_total{bucket="1_2"} 43
telemt_desync_frames_bucket_total{bucket="3_10"} 58
telemt_desync_frames_bucket_total{bucket="gt_10"} 71
telemt_pool_swap_total 4
telemt_pool_force_close_total 98
telemt_me_writer_removed_unexpected_total 261
telemt_me_writer_restored_same_endpoint_total 252
telemt_me_writer_removed_unexpected_minus_restored_total 9
telemt_user_connections_total{user="hello"} 85133
telemt_user_connections_current{user="hello"} 180
telemt_user_octets_from_client{user="hello"} 1037184664 (989.14 MB)
telemt_user_octets_to_client{user="hello"} 29182719684 (27.18 GB)
telemt_user_unique_ips_current{user="hello"} 21
```

## server4

```
telemt 3.2.1

telemt_uptime_seconds 44273.8 (12h 17m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 550065
telemt_connections_bad_total 79695
telemt_handshake_timeouts_total 14732
telemt_upstream_connect_attempt_total 20028
telemt_upstream_connect_success_total 20026
telemt_upstream_connect_attempts_per_request{bucket="1"} 20026
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11551
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8471
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_me_keepalive_timeout_total 251
telemt_me_reconnect_attempts_total 2739
telemt_me_reconnect_success_total 2721
telemt_me_reader_eof_total 2775
telemt_me_idle_close_by_peer_total 2775
telemt_me_route_drop_no_conn_total 185665
telemt_me_route_drop_channel_closed_total 1
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_single_endpoint_shadow_rotate_total 181
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 720
telemt_desync_full_logged_total 303
telemt_desync_suppressed_total 417
telemt_desync_frames_bucket_total{bucket="1_2"} 222
telemt_desync_frames_bucket_total{bucket="3_10"} 207
telemt_desync_frames_bucket_total{bucket="gt_10"} 291
telemt_pool_swap_total 17
telemt_pool_force_close_total 484
telemt_pool_stale_pick_total 22
telemt_me_writer_removed_unexpected_total 2776
telemt_me_writer_restored_same_endpoint_total 2694
telemt_me_writer_removed_unexpected_minus_restored_total 82
telemt_user_connections_total{user="hello"} 427135
telemt_user_connections_current{user="hello"} 117
telemt_user_octets_from_client{user="hello"} 5839687660 (5.44 GB)
telemt_user_octets_to_client{user="hello"} 159649634028 (148.69 GB)
telemt_user_unique_ips_current{user="hello"} 15
```

## server5

```
telemt 3.2.1

telemt_uptime_seconds 44633.1 (12h 23m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 536153
telemt_connections_bad_total 3853
telemt_handshake_timeouts_total 5909
telemt_upstream_connect_attempt_total 28884
telemt_upstream_connect_success_total 28729
telemt_upstream_connect_fail_total 61
telemt_upstream_connect_attempts_per_request{bucket="1"} 28729
telemt_upstream_connect_attempts_per_request{bucket="2"} 61
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 16676
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11947
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 106
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 61
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 434
telemt_me_reconnect_attempts_total 6529
telemt_me_reconnect_success_total 6509
telemt_me_reader_eof_total 6753
telemt_me_idle_close_by_peer_total 6752
telemt_me_route_drop_no_conn_total 235975
telemt_me_route_drop_channel_closed_total 2
telemt_me_hardswap_pending_ttl_expired_total 9
telemt_me_single_endpoint_shadow_rotate_total 180
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 828
telemt_desync_full_logged_total 301
telemt_desync_suppressed_total 527
telemt_desync_frames_bucket_total{bucket="1_2"} 168
telemt_desync_frames_bucket_total{bucket="3_10"} 350
telemt_desync_frames_bucket_total{bucket="gt_10"} 310
telemt_pool_swap_total 10
telemt_pool_force_close_total 420
telemt_pool_stale_pick_total 189
telemt_me_writer_removed_unexpected_total 6758
telemt_me_writer_restored_same_endpoint_total 6487
telemt_me_writer_removed_unexpected_minus_restored_total 271
telemt_user_connections_total{user="hello"} 485623
telemt_user_connections_current{user="hello"} 106
telemt_user_octets_from_client{user="hello"} 7376999728 (6.87 GB)
telemt_user_octets_to_client{user="hello"} 162488946248 (151.33 GB)
telemt_user_unique_ips_current{user="hello"} 23
```