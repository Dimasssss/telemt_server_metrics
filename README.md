# Server Metrics 2026-03-06 17:23:11 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.4

telemt_uptime_seconds 25273.8 (7h 1m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 752551
telemt_connections_bad_total 12805
telemt_handshake_timeouts_total 3266
telemt_upstream_connect_attempt_total 13059
telemt_upstream_connect_success_total 12981
telemt_upstream_connect_fail_total 32
telemt_upstream_connect_attempts_per_request{bucket="1"} 13013
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7006
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5894
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 46
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 35
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 32
telemt_me_keepalive_timeout_total 172
telemt_me_reconnect_attempts_total 2659
telemt_me_reconnect_success_total 2640
telemt_me_reader_eof_total 2766
telemt_me_idle_close_by_peer_total 2766
telemt_me_route_drop_no_conn_total 318512
telemt_me_route_drop_channel_closed_total 3
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_single_endpoint_shadow_rotate_total 100
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_floor_mode_switch_all_total 2
telemt_me_floor_mode_switch_total{from="static",to="adaptive"} 1
telemt_me_floor_mode_switch_total{from="adaptive",to="static"} 1
telemt_desync_total 3842
telemt_desync_full_logged_total 935
telemt_desync_suppressed_total 2907
telemt_desync_frames_bucket_total{bucket="1_2"} 905
telemt_desync_frames_bucket_total{bucket="3_10"} 1346
telemt_desync_frames_bucket_total{bucket="gt_10"} 1591
telemt_pool_swap_total 4
telemt_pool_force_close_total 234
telemt_me_writer_removed_unexpected_total 2769
telemt_me_writer_restored_same_endpoint_total 2634
telemt_me_writer_removed_unexpected_minus_restored_total 135
telemt_user_connections_total{user="hello"} 645831
telemt_user_connections_current{user="hello"} 1043
telemt_user_octets_from_client{user="hello"} 13632120556 (12.70 GB)
telemt_user_octets_to_client{user="hello"} 235492556228 (219.32 GB)
telemt_user_unique_ips_current{user="hello"} 279
telemt_user_unique_ips_recent_window{user="hello"} 156
```

## server2

```
telemt 3.3.4

telemt_uptime_seconds 25273.8 (7h 1m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 279802
telemt_connections_bad_total 977
telemt_handshake_timeouts_total 8253
telemt_upstream_connect_attempt_total 11338
telemt_upstream_connect_success_total 11305
telemt_upstream_connect_fail_total 33
telemt_upstream_connect_attempts_per_request{bucket="1"} 11338
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5401
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5903
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 33
telemt_me_keepalive_timeout_total 148
telemt_me_reconnect_attempts_total 966
telemt_me_reconnect_success_total 943
telemt_me_reader_eof_total 995
telemt_me_idle_close_by_peer_total 995
telemt_me_route_drop_no_conn_total 152868
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_single_endpoint_shadow_rotate_total 102
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_floor_mode_switch_all_total 2
telemt_me_floor_mode_switch_total{from="static",to="adaptive"} 1
telemt_me_floor_mode_switch_total{from="adaptive",to="static"} 1
telemt_desync_total 892
telemt_desync_full_logged_total 283
telemt_desync_suppressed_total 609
telemt_desync_frames_bucket_total{bucket="1_2"} 166
telemt_desync_frames_bucket_total{bucket="3_10"} 324
telemt_desync_frames_bucket_total{bucket="gt_10"} 402
telemt_pool_swap_total 7
telemt_pool_force_close_total 282
telemt_me_writer_removed_unexpected_total 996
telemt_me_writer_restored_same_endpoint_total 943
telemt_me_writer_removed_unexpected_minus_restored_total 53
telemt_user_connections_total{user="hello"} 257666
telemt_user_connections_current{user="hello"} 426
telemt_user_octets_from_client{user="hello"} 3121948596 (2.91 GB)
telemt_user_octets_to_client{user="hello"} 104056047856 (96.91 GB)
telemt_user_unique_ips_current{user="hello"} 120
telemt_user_unique_ips_recent_window{user="hello"} 75
```

## server3

```
telemt 3.3.4

telemt_uptime_seconds 25273.5 (7h 1m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 548910
telemt_connections_bad_total 5540
telemt_handshake_timeouts_total 52501
telemt_upstream_connect_attempt_total 22657
telemt_upstream_connect_success_total 22548
telemt_upstream_connect_fail_total 79
telemt_upstream_connect_attempts_per_request{bucket="1"} 22627
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12412
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10084
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 50
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 79
telemt_me_keepalive_timeout_total 332
telemt_me_reconnect_attempts_total 7950
telemt_me_reconnect_success_total 7921
telemt_me_reader_eof_total 8416
telemt_me_idle_close_by_peer_total 8416
telemt_me_route_drop_no_conn_total 290729
telemt_me_endpoint_quarantine_total 1
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_single_endpoint_shadow_rotate_total 102
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_floor_mode_switch_all_total 2
telemt_me_floor_mode_switch_total{from="static",to="adaptive"} 1
telemt_me_floor_mode_switch_total{from="adaptive",to="static"} 1
telemt_desync_total 1365
telemt_desync_full_logged_total 397
telemt_desync_suppressed_total 968
telemt_desync_frames_bucket_total{bucket="1_2"} 309
telemt_desync_frames_bucket_total{bucket="3_10"} 514
telemt_desync_frames_bucket_total{bucket="gt_10"} 542
telemt_pool_swap_total 2
telemt_pool_force_close_total 169
telemt_pool_stale_pick_total 381
telemt_me_writer_removed_unexpected_total 8431
telemt_me_writer_restored_same_endpoint_total 7914
telemt_me_writer_restored_fallback_total 2
telemt_me_writer_removed_unexpected_minus_restored_total 515
telemt_user_connections_total{user="hello"} 472520
telemt_user_connections_current{user="hello"} 642
telemt_user_octets_from_client{user="hello"} 7116588988 (6.63 GB)
telemt_user_octets_to_client{user="hello"} 146395938360 (136.34 GB)
telemt_user_unique_ips_current{user="hello"} 191
telemt_user_unique_ips_recent_window{user="hello"} 104
```

## server4

```
telemt 3.3.4

telemt_uptime_seconds 24589.7 (6h 49m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 527447
telemt_connections_bad_total 178645
telemt_handshake_timeouts_total 13486
telemt_upstream_connect_attempt_total 16665
telemt_upstream_connect_success_total 16663
telemt_upstream_connect_attempts_per_request{bucket="1"} 16663
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9443
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7220
telemt_me_keepalive_timeout_total 231
telemt_me_reconnect_attempts_total 4578
telemt_me_reconnect_success_total 4555
telemt_me_reader_eof_total 4769
telemt_me_idle_close_by_peer_total 4769
telemt_me_route_drop_no_conn_total 171351
telemt_me_route_drop_channel_closed_total 2
telemt_me_endpoint_quarantine_total 1
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_single_endpoint_shadow_rotate_total 107
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_floor_mode_switch_all_total 1
telemt_me_floor_mode_switch_total{from="static",to="adaptive"} 1
telemt_desync_total 361
telemt_desync_full_logged_total 138
telemt_desync_suppressed_total 223
telemt_desync_frames_bucket_total{bucket="1_2"} 91
telemt_desync_frames_bucket_total{bucket="3_10"} 123
telemt_desync_frames_bucket_total{bucket="gt_10"} 147
telemt_pool_swap_total 4
telemt_pool_force_close_total 192
telemt_me_writer_removed_unexpected_total 4776
telemt_me_writer_restored_same_endpoint_total 4554
telemt_me_writer_restored_fallback_total 1
telemt_me_writer_removed_unexpected_minus_restored_total 221
telemt_user_connections_total{user="hello"} 298014
telemt_user_connections_current{user="hello"} 550
telemt_user_octets_from_client{user="hello"} 4979598768 (4.64 GB)
telemt_user_octets_to_client{user="hello"} 103820653480 (96.69 GB)
telemt_user_unique_ips_current{user="hello"} 134
telemt_user_unique_ips_recent_window{user="hello"} 76
```

## server5

```
telemt 3.3.4

telemt_uptime_seconds 25273.9 (7h 1m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 463104
telemt_connections_bad_total 11135
telemt_handshake_timeouts_total 4578
telemt_upstream_connect_attempt_total 10773
telemt_upstream_connect_success_total 10756
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 10757
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5822
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4868
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 64
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_keepalive_timeout_total 178
telemt_me_reconnect_attempts_total 1787
telemt_me_reconnect_success_total 1767
telemt_me_reader_eof_total 1867
telemt_me_idle_close_by_peer_total 1866
telemt_me_route_drop_no_conn_total 221364
telemt_me_route_drop_channel_closed_total 6
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_single_endpoint_shadow_rotate_total 97
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_floor_mode_switch_all_total 2
telemt_me_floor_mode_switch_total{from="static",to="adaptive"} 1
telemt_me_floor_mode_switch_total{from="adaptive",to="static"} 1
telemt_desync_total 886
telemt_desync_full_logged_total 316
telemt_desync_suppressed_total 570
telemt_desync_frames_bucket_total{bucket="1_2"} 394
telemt_desync_frames_bucket_total{bucket="3_10"} 260
telemt_desync_frames_bucket_total{bucket="gt_10"} 232
telemt_pool_swap_total 8
telemt_pool_force_close_total 297
telemt_pool_stale_pick_total 293
telemt_me_writer_removed_unexpected_total 1871
telemt_me_writer_restored_same_endpoint_total 1764
telemt_me_writer_removed_unexpected_minus_restored_total 107
telemt_user_connections_total{user="hello"} 425077
telemt_user_connections_current{user="hello"} 511
telemt_user_octets_from_client{user="hello"} 20263367940 (18.87 GB)
telemt_user_octets_to_client{user="hello"} 208090095012 (193.80 GB)
telemt_user_unique_ips_current{user="hello"} 130
telemt_user_unique_ips_recent_window{user="hello"} 80
```