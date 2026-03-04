# Server Metrics 2026-03-04 15:28:13 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.1.6

telemt_uptime_seconds 65855.8 (18h 17m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1234198
telemt_connections_bad_total 15672
telemt_handshake_timeouts_total 22286
telemt_upstream_connect_attempt_total 38314
telemt_upstream_connect_success_total 38141
telemt_upstream_connect_fail_total 68
telemt_upstream_connect_attempts_per_request{bucket="1"} 38141
telemt_upstream_connect_attempts_per_request{bucket="2"} 68
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 20979
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 17086
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 42
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 34
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 68
telemt_me_keepalive_timeout_total 439
telemt_me_reconnect_attempts_total 8187
telemt_me_reconnect_success_total 8125
telemt_me_reader_eof_total 8390
telemt_me_idle_close_by_peer_total 8389
telemt_me_route_drop_no_conn_total 454600
telemt_me_route_drop_channel_closed_total 3
telemt_me_hardswap_pending_ttl_expired_total 14
telemt_me_single_endpoint_shadow_rotate_total 258
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 2439
telemt_desync_full_logged_total 792
telemt_desync_suppressed_total 1647
telemt_desync_frames_bucket_total{bucket="1_2"} 728
telemt_desync_frames_bucket_total{bucket="3_10"} 910
telemt_desync_frames_bucket_total{bucket="gt_10"} 801
telemt_pool_swap_total 17
telemt_pool_force_close_total 715
telemt_pool_stale_pick_total 76
telemt_me_writer_removed_unexpected_total 8390
telemt_me_writer_restored_same_endpoint_total 8103
telemt_me_writer_removed_unexpected_minus_restored_total 287
telemt_user_connections_total{user="hello"} 995075
telemt_user_connections_current{user="hello"} 1091
telemt_user_octets_from_client{user="hello"} 13242675676 (12.33 GB)
telemt_user_octets_to_client{user="hello"} 335049434980 (312.04 GB)
telemt_user_unique_ips_current{user="hello"} 105
```

## server2

```
telemt 3.1.6

telemt_uptime_seconds 65852.3 (18h 17m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 468479
telemt_connections_bad_total 4114
telemt_handshake_timeouts_total 30433
telemt_upstream_connect_attempt_total 119605
telemt_upstream_connect_success_total 117891
telemt_upstream_connect_fail_total 818
telemt_upstream_connect_attempts_per_request{bucket="1"} 117885
telemt_upstream_connect_attempts_per_request{bucket="2"} 824
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 76614
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 41253
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 24
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 818
telemt_me_keepalive_timeout_total 1571
telemt_me_reconnect_attempts_total 65358
telemt_me_reconnect_success_total 65255
telemt_me_reader_eof_total 66949
telemt_me_idle_close_by_peer_total 66948
telemt_me_route_drop_no_conn_total 190571
telemt_me_hardswap_pending_ttl_expired_total 20
telemt_me_single_endpoint_outage_enter_total 2
telemt_me_single_endpoint_outage_exit_total 2
telemt_me_single_endpoint_outage_reconnect_attempt_total 37
telemt_me_single_endpoint_outage_reconnect_success_total 1
telemt_me_single_endpoint_quarantine_bypass_total 37
telemt_me_single_endpoint_shadow_rotate_total 274
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 1113
telemt_desync_full_logged_total 339
telemt_desync_suppressed_total 774
telemt_desync_frames_bucket_total{bucket="1_2"} 211
telemt_desync_frames_bucket_total{bucket="3_10"} 447
telemt_desync_frames_bucket_total{bucket="gt_10"} 455
telemt_pool_swap_total 4
telemt_pool_force_close_total 281
telemt_pool_stale_pick_total 56
telemt_me_writer_removed_unexpected_total 67029
telemt_me_writer_restored_same_endpoint_total 65230
telemt_me_writer_removed_unexpected_minus_restored_total 1799
telemt_user_connections_total{user="hello"} 370783
telemt_user_connections_current{user="hello"} 487
telemt_user_octets_from_client{user="hello"} 5790231484 (5.39 GB)
telemt_user_octets_to_client{user="hello"} 117238891812 (109.19 GB)
telemt_user_unique_ips_current{user="hello"} 40
```

## server3

```
telemt 3.1.6

telemt_uptime_seconds 65851.1 (18h 17m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 946693
telemt_connections_bad_total 195201
telemt_handshake_timeouts_total 29973
telemt_upstream_connect_attempt_total 87369
telemt_upstream_connect_success_total 86784
telemt_upstream_connect_fail_total 282
telemt_upstream_connect_attempts_per_request{bucket="1"} 86783
telemt_upstream_connect_attempts_per_request{bucket="2"} 283
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 51379
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 35175
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 230
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 282
telemt_me_keepalive_timeout_total 1133
telemt_me_reconnect_attempts_total 39139
telemt_me_reconnect_success_total 39036
telemt_me_reader_eof_total 41079
telemt_me_idle_close_by_peer_total 41074
telemt_me_route_drop_no_conn_total 343341
telemt_me_hardswap_pending_ttl_expired_total 19
telemt_me_single_endpoint_shadow_rotate_total 271
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 2000
telemt_desync_full_logged_total 662
telemt_desync_suppressed_total 1338
telemt_desync_frames_bucket_total{bucket="1_2"} 611
telemt_desync_frames_bucket_total{bucket="3_10"} 645
telemt_desync_frames_bucket_total{bucket="gt_10"} 744
telemt_pool_swap_total 7
telemt_pool_force_close_total 381
telemt_me_writer_removed_unexpected_total 41091
telemt_me_writer_restored_same_endpoint_total 39014
telemt_me_writer_removed_unexpected_minus_restored_total 2077
telemt_user_connections_total{user="hello"} 676168
telemt_user_connections_current{user="hello"} 635
telemt_user_octets_from_client{user="hello"} 13809927412 (12.86 GB)
telemt_user_octets_to_client{user="hello"} 229206222644 (213.46 GB)
telemt_user_unique_ips_current{user="hello"} 62
```

## server4

```
telemt 3.2.1

telemt_uptime_seconds 12528.5 (3h 28m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 192247
telemt_connections_bad_total 19484
telemt_handshake_timeouts_total 5765
telemt_upstream_connect_attempt_total 5261
telemt_upstream_connect_success_total 5261
telemt_upstream_connect_attempts_per_request{bucket="1"} 5261
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3116
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2145
telemt_me_keepalive_timeout_total 60
telemt_me_reconnect_attempts_total 858
telemt_me_reconnect_success_total 869
telemt_me_reader_eof_total 877
telemt_me_idle_close_by_peer_total 877
telemt_me_route_drop_no_conn_total 60327
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_shadow_rotate_total 49
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 208
telemt_desync_full_logged_total 77
telemt_desync_suppressed_total 131
telemt_desync_frames_bucket_total{bucket="1_2"} 63
telemt_desync_frames_bucket_total{bucket="3_10"} 55
telemt_desync_frames_bucket_total{bucket="gt_10"} 90
telemt_pool_swap_total 4
telemt_pool_force_close_total 146
telemt_me_writer_removed_unexpected_total 877
telemt_me_writer_restored_same_endpoint_total 848
telemt_me_writer_removed_unexpected_minus_restored_total 29
telemt_user_connections_total{user="hello"} 160445
telemt_user_connections_current{user="hello"} 503
telemt_user_octets_from_client{user="hello"} 2034473528 (1.89 GB)
telemt_user_octets_to_client{user="hello"} 67934491048 (63.27 GB)
telemt_user_unique_ips_current{user="hello"} 48
```

## server5

```
telemt 3.2.1

telemt_uptime_seconds 12887.8 (3h 34m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 218063
telemt_connections_bad_total 2231
telemt_handshake_timeouts_total 3423
telemt_upstream_connect_attempt_total 6706
telemt_upstream_connect_success_total 6675
telemt_upstream_connect_fail_total 15
telemt_upstream_connect_attempts_per_request{bucket="1"} 6675
telemt_upstream_connect_attempts_per_request{bucket="2"} 15
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3863
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2803
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 9
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 15
telemt_me_keepalive_timeout_total 94
telemt_me_reconnect_attempts_total 1285
telemt_me_reconnect_success_total 1293
telemt_me_reader_eof_total 1319
telemt_me_idle_close_by_peer_total 1319
telemt_me_route_drop_no_conn_total 82553
telemt_me_route_drop_channel_closed_total 2
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_single_endpoint_shadow_rotate_total 55
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 503
telemt_desync_full_logged_total 193
telemt_desync_suppressed_total 310
telemt_desync_frames_bucket_total{bucket="1_2"} 74
telemt_desync_frames_bucket_total{bucket="3_10"} 214
telemt_desync_frames_bucket_total{bucket="gt_10"} 215
telemt_pool_swap_total 3
telemt_pool_force_close_total 139
telemt_me_writer_removed_unexpected_total 1319
telemt_me_writer_restored_same_endpoint_total 1273
telemt_me_writer_removed_unexpected_minus_restored_total 46
telemt_user_connections_total{user="hello"} 189871
telemt_user_connections_current{user="hello"} 635
telemt_user_octets_from_client{user="hello"} 3050154928 (2.84 GB)
telemt_user_octets_to_client{user="hello"} 54347897132 (50.62 GB)
telemt_user_unique_ips_current{user="hello"} 52
```