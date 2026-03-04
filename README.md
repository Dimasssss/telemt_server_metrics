# Server Metrics 2026-03-04 14:57:27 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.1.6

telemt_uptime_seconds 64009.7 (17h 46m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1187097
telemt_connections_bad_total 14021
telemt_handshake_timeouts_total 21790
telemt_upstream_connect_attempt_total 37574
telemt_upstream_connect_success_total 37407
telemt_upstream_connect_fail_total 65
telemt_upstream_connect_attempts_per_request{bucket="1"} 37407
telemt_upstream_connect_attempts_per_request{bucket="2"} 65
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 20572
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 16760
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 42
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 33
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 65
telemt_me_keepalive_timeout_total 430
telemt_me_reconnect_attempts_total 8178
telemt_me_reconnect_success_total 8116
telemt_me_reader_eof_total 8381
telemt_me_idle_close_by_peer_total 8380
telemt_me_route_drop_no_conn_total 437479
telemt_me_route_drop_channel_closed_total 3
telemt_me_hardswap_pending_ttl_expired_total 14
telemt_me_single_endpoint_shadow_rotate_total 251
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 2283
telemt_desync_full_logged_total 748
telemt_desync_suppressed_total 1535
telemt_desync_frames_bucket_total{bucket="1_2"} 673
telemt_desync_frames_bucket_total{bucket="3_10"} 869
telemt_desync_frames_bucket_total{bucket="gt_10"} 741
telemt_pool_swap_total 17
telemt_pool_force_close_total 715
telemt_pool_stale_pick_total 76
telemt_me_writer_removed_unexpected_total 8381
telemt_me_writer_restored_same_endpoint_total 8094
telemt_me_writer_removed_unexpected_minus_restored_total 287
telemt_user_connections_total{user="hello"} 953023
telemt_user_connections_current{user="hello"} 1173
telemt_user_octets_from_client{user="hello"} 12599383552 (11.73 GB)
telemt_user_octets_to_client{user="hello"} 320920429448 (298.88 GB)
telemt_user_unique_ips_current{user="hello"} 112
```

## server2

```
telemt 3.1.6

telemt_uptime_seconds 64006.1 (17h 46m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 451115
telemt_connections_bad_total 3756
telemt_handshake_timeouts_total 30226
telemt_upstream_connect_attempt_total 115503
telemt_upstream_connect_success_total 113813
telemt_upstream_connect_fail_total 807
telemt_upstream_connect_attempts_per_request{bucket="1"} 113807
telemt_upstream_connect_attempts_per_request{bucket="2"} 813
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 74127
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 39662
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 24
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 807
telemt_me_keepalive_timeout_total 1527
telemt_me_reconnect_attempts_total 63073
telemt_me_reconnect_success_total 62972
telemt_me_reader_eof_total 64607
telemt_me_idle_close_by_peer_total 64606
telemt_me_route_drop_no_conn_total 183615
telemt_me_hardswap_pending_ttl_expired_total 20
telemt_me_single_endpoint_outage_enter_total 2
telemt_me_single_endpoint_outage_exit_total 2
telemt_me_single_endpoint_outage_reconnect_attempt_total 37
telemt_me_single_endpoint_outage_reconnect_success_total 1
telemt_me_single_endpoint_quarantine_bypass_total 37
telemt_me_single_endpoint_shadow_rotate_total 267
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 1038
telemt_desync_full_logged_total 313
telemt_desync_suppressed_total 725
telemt_desync_frames_bucket_total{bucket="1_2"} 197
telemt_desync_frames_bucket_total{bucket="3_10"} 426
telemt_desync_frames_bucket_total{bucket="gt_10"} 415
telemt_pool_swap_total 4
telemt_pool_force_close_total 281
telemt_pool_stale_pick_total 56
telemt_me_writer_removed_unexpected_total 64687
telemt_me_writer_restored_same_endpoint_total 62947
telemt_me_writer_removed_unexpected_minus_restored_total 1740
telemt_user_connections_total{user="hello"} 354261
telemt_user_connections_current{user="hello"} 416
telemt_user_octets_from_client{user="hello"} 5665738760 (5.28 GB)
telemt_user_octets_to_client{user="hello"} 113248918604 (105.47 GB)
telemt_user_unique_ips_current{user="hello"} 39
```

## server3

```
telemt 3.1.6

telemt_uptime_seconds 64005.0 (17h 46m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 907706
telemt_connections_bad_total 189917
telemt_handshake_timeouts_total 29735
telemt_upstream_connect_attempt_total 85148
telemt_upstream_connect_success_total 84592
telemt_upstream_connect_fail_total 268
telemt_upstream_connect_attempts_per_request{bucket="1"} 84591
telemt_upstream_connect_attempts_per_request{bucket="2"} 269
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 50037
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 34328
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 227
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 268
telemt_me_keepalive_timeout_total 1104
telemt_me_reconnect_attempts_total 38236
telemt_me_reconnect_success_total 38136
telemt_me_reader_eof_total 40136
telemt_me_idle_close_by_peer_total 40132
telemt_me_route_drop_no_conn_total 329692
telemt_me_hardswap_pending_ttl_expired_total 18
telemt_me_single_endpoint_shadow_rotate_total 263
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 1912
telemt_desync_full_logged_total 633
telemt_desync_suppressed_total 1279
telemt_desync_frames_bucket_total{bucket="1_2"} 594
telemt_desync_frames_bucket_total{bucket="3_10"} 614
telemt_desync_frames_bucket_total{bucket="gt_10"} 704
telemt_pool_swap_total 7
telemt_pool_force_close_total 381
telemt_me_writer_removed_unexpected_total 40148
telemt_me_writer_restored_same_endpoint_total 38114
telemt_me_writer_removed_unexpected_minus_restored_total 2034
telemt_user_connections_total{user="hello"} 643730
telemt_user_connections_current{user="hello"} 729
telemt_user_octets_from_client{user="hello"} 13155693324 (12.25 GB)
telemt_user_octets_to_client{user="hello"} 218529445572 (203.52 GB)
telemt_user_unique_ips_current{user="hello"} 65
```

## server4

```
telemt 3.2.1

telemt_uptime_seconds 10682.4 (2h 58m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 157960
telemt_connections_bad_total 14569
telemt_handshake_timeouts_total 5125
telemt_upstream_connect_attempt_total 4847
telemt_upstream_connect_success_total 4847
telemt_upstream_connect_attempts_per_request{bucket="1"} 4847
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2948
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1899
telemt_me_keepalive_timeout_total 53
telemt_me_reconnect_attempts_total 853
telemt_me_reconnect_success_total 865
telemt_me_reader_eof_total 872
telemt_me_idle_close_by_peer_total 872
telemt_me_route_drop_no_conn_total 52221
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_shadow_rotate_total 44
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 189
telemt_desync_full_logged_total 72
telemt_desync_suppressed_total 117
telemt_desync_frames_bucket_total{bucket="1_2"} 52
telemt_desync_frames_bucket_total{bucket="3_10"} 54
telemt_desync_frames_bucket_total{bucket="gt_10"} 83
telemt_pool_swap_total 3
telemt_pool_force_close_total 110
telemt_me_writer_removed_unexpected_total 872
telemt_me_writer_restored_same_endpoint_total 844
telemt_me_writer_removed_unexpected_minus_restored_total 28
telemt_user_connections_total{user="hello"} 133237
telemt_user_connections_current{user="hello"} 449
telemt_user_octets_from_client{user="hello"} 1757496492 (1.64 GB)
telemt_user_octets_to_client{user="hello"} 62017074236 (57.76 GB)
telemt_user_unique_ips_current{user="hello"} 45
```

## server5

```
telemt 3.2.1

telemt_uptime_seconds 11041.5 (3h 4m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 188875
telemt_connections_bad_total 1858
telemt_handshake_timeouts_total 3085
telemt_upstream_connect_attempt_total 6051
telemt_upstream_connect_success_total 6020
telemt_upstream_connect_fail_total 15
telemt_upstream_connect_attempts_per_request{bucket="1"} 6020
telemt_upstream_connect_attempts_per_request{bucket="2"} 15
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3502
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2509
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 9
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 15
telemt_me_keepalive_timeout_total 84
telemt_me_reconnect_attempts_total 1228
telemt_me_reconnect_success_total 1237
telemt_me_reader_eof_total 1262
telemt_me_idle_close_by_peer_total 1262
telemt_me_route_drop_no_conn_total 67847
telemt_me_route_drop_channel_closed_total 2
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_single_endpoint_shadow_rotate_total 48
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 460
telemt_desync_full_logged_total 174
telemt_desync_suppressed_total 286
telemt_desync_frames_bucket_total{bucket="1_2"} 61
telemt_desync_frames_bucket_total{bucket="3_10"} 197
telemt_desync_frames_bucket_total{bucket="gt_10"} 202
telemt_pool_swap_total 2
telemt_pool_force_close_total 101
telemt_me_writer_removed_unexpected_total 1262
telemt_me_writer_restored_same_endpoint_total 1217
telemt_me_writer_removed_unexpected_minus_restored_total 45
telemt_user_connections_total{user="hello"} 163663
telemt_user_connections_current{user="hello"} 619
telemt_user_octets_from_client{user="hello"} 2712439220 (2.53 GB)
telemt_user_octets_to_client{user="hello"} 45261120328 (42.15 GB)
telemt_user_unique_ips_current{user="hello"} 52
```