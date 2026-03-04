# Server Metrics 2026-03-04 14:26:43 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.1.6

telemt_uptime_seconds 62165.4 (17h 16m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1140741
telemt_connections_bad_total 13927
telemt_handshake_timeouts_total 20517
telemt_upstream_connect_attempt_total 37114
telemt_upstream_connect_success_total 36947
telemt_upstream_connect_fail_total 65
telemt_upstream_connect_attempts_per_request{bucket="1"} 36947
telemt_upstream_connect_attempts_per_request{bucket="2"} 65
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 20324
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 16548
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 42
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 33
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 65
telemt_me_keepalive_timeout_total 427
telemt_me_reconnect_attempts_total 8165
telemt_me_reconnect_success_total 8106
telemt_me_reader_eof_total 8370
telemt_me_idle_close_by_peer_total 8369
telemt_me_route_drop_no_conn_total 422111
telemt_me_route_drop_channel_closed_total 3
telemt_me_hardswap_pending_ttl_expired_total 14
telemt_me_single_endpoint_shadow_rotate_total 243
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 2044
telemt_desync_full_logged_total 678
telemt_desync_suppressed_total 1366
telemt_desync_frames_bucket_total{bucket="1_2"} 597
telemt_desync_frames_bucket_total{bucket="3_10"} 778
telemt_desync_frames_bucket_total{bucket="gt_10"} 669
telemt_pool_swap_total 16
telemt_pool_force_close_total 682
telemt_pool_stale_pick_total 76
telemt_me_writer_removed_unexpected_total 8370
telemt_me_writer_restored_same_endpoint_total 8084
telemt_me_writer_removed_unexpected_minus_restored_total 286
telemt_user_connections_total{user="hello"} 909930
telemt_user_connections_current{user="hello"} 1189
telemt_user_octets_from_client{user="hello"} 12064402720 (11.24 GB)
telemt_user_octets_to_client{user="hello"} 305842778496 (284.84 GB)
telemt_user_unique_ips_current{user="hello"} 99
```

## server2

```
telemt 3.1.6

telemt_uptime_seconds 62162.0 (17h 16m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 433762
telemt_connections_bad_total 3713
telemt_handshake_timeouts_total 29577
telemt_upstream_connect_attempt_total 111909
telemt_upstream_connect_success_total 110239
telemt_upstream_connect_fail_total 797
telemt_upstream_connect_attempts_per_request{bucket="1"} 110233
telemt_upstream_connect_attempts_per_request{bucket="2"} 803
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 72144
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 38071
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 24
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 797
telemt_me_keepalive_timeout_total 1497
telemt_me_reconnect_attempts_total 61286
telemt_me_reconnect_success_total 61188
telemt_me_reader_eof_total 62797
telemt_me_idle_close_by_peer_total 62796
telemt_me_route_drop_no_conn_total 176468
telemt_me_hardswap_pending_ttl_expired_total 19
telemt_me_single_endpoint_outage_enter_total 2
telemt_me_single_endpoint_outage_exit_total 2
telemt_me_single_endpoint_outage_reconnect_attempt_total 37
telemt_me_single_endpoint_outage_reconnect_success_total 1
telemt_me_single_endpoint_quarantine_bypass_total 37
telemt_me_single_endpoint_shadow_rotate_total 259
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 913
telemt_desync_full_logged_total 274
telemt_desync_suppressed_total 639
telemt_desync_frames_bucket_total{bucket="1_2"} 174
telemt_desync_frames_bucket_total{bucket="3_10"} 378
telemt_desync_frames_bucket_total{bucket="gt_10"} 361
telemt_pool_swap_total 4
telemt_pool_force_close_total 281
telemt_pool_stale_pick_total 56
telemt_me_writer_removed_unexpected_total 62877
telemt_me_writer_restored_same_endpoint_total 61163
telemt_me_writer_removed_unexpected_minus_restored_total 1714
telemt_user_connections_total{user="hello"} 338012
telemt_user_connections_current{user="hello"} 419
telemt_user_octets_from_client{user="hello"} 4884415940 (4.55 GB)
telemt_user_octets_to_client{user="hello"} 107320576276 (99.95 GB)
telemt_user_unique_ips_current{user="hello"} 44
```

## server3

```
telemt 3.1.6

telemt_uptime_seconds 62160.7 (17h 16m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 865572
telemt_connections_bad_total 184729
telemt_handshake_timeouts_total 29257
telemt_upstream_connect_attempt_total 83970
telemt_upstream_connect_success_total 83445
telemt_upstream_connect_fail_total 253
telemt_upstream_connect_attempts_per_request{bucket="1"} 83444
telemt_upstream_connect_attempts_per_request{bucket="2"} 254
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 49299
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 33923
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 223
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 253
telemt_me_keepalive_timeout_total 1092
telemt_me_reconnect_attempts_total 38000
telemt_me_reconnect_success_total 37901
telemt_me_reader_eof_total 39898
telemt_me_idle_close_by_peer_total 39894
telemt_me_route_drop_no_conn_total 314485
telemt_me_hardswap_pending_ttl_expired_total 17
telemt_me_single_endpoint_shadow_rotate_total 255
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 1775
telemt_desync_full_logged_total 593
telemt_desync_suppressed_total 1182
telemt_desync_frames_bucket_total{bucket="1_2"} 571
telemt_desync_frames_bucket_total{bucket="3_10"} 573
telemt_desync_frames_bucket_total{bucket="gt_10"} 631
telemt_pool_swap_total 7
telemt_pool_force_close_total 381
telemt_me_writer_removed_unexpected_total 39910
telemt_me_writer_restored_same_endpoint_total 37879
telemt_me_writer_removed_unexpected_minus_restored_total 2031
telemt_user_connections_total{user="hello"} 609820
telemt_user_connections_current{user="hello"} 685
telemt_user_octets_from_client{user="hello"} 12635934892 (11.77 GB)
telemt_user_octets_to_client{user="hello"} 208036354476 (193.75 GB)
telemt_user_unique_ips_current{user="hello"} 67
```

## server4

```
telemt 3.2.1

telemt_uptime_seconds 8838.2 (2h 27m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 115365
telemt_connections_bad_total 12037
telemt_handshake_timeouts_total 4213
telemt_upstream_connect_attempt_total 4578
telemt_upstream_connect_success_total 4578
telemt_upstream_connect_attempts_per_request{bucket="1"} 4578
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2808
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1770
telemt_me_keepalive_timeout_total 51
telemt_me_reconnect_attempts_total 851
telemt_me_reconnect_success_total 863
telemt_me_reader_eof_total 870
telemt_me_idle_close_by_peer_total 870
telemt_me_route_drop_no_conn_total 42390
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_shadow_rotate_total 37
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 163
telemt_desync_full_logged_total 65
telemt_desync_suppressed_total 98
telemt_desync_frames_bucket_total{bucket="1_2"} 37
telemt_desync_frames_bucket_total{bucket="3_10"} 51
telemt_desync_frames_bucket_total{bucket="gt_10"} 75
telemt_pool_swap_total 2
telemt_pool_force_close_total 93
telemt_me_writer_removed_unexpected_total 870
telemt_me_writer_restored_same_endpoint_total 842
telemt_me_writer_removed_unexpected_minus_restored_total 28
telemt_user_connections_total{user="hello"} 97185
telemt_user_connections_current{user="hello"} 469
telemt_user_octets_from_client{user="hello"} 1553141160 (1.45 GB)
telemt_user_octets_to_client{user="hello"} 54255421668 (50.53 GB)
telemt_user_unique_ips_current{user="hello"} 56
```

## server5

```
telemt 3.2.1

telemt_uptime_seconds 9197.5 (2h 33m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 158452
telemt_connections_bad_total 1675
telemt_handshake_timeouts_total 2656
telemt_upstream_connect_attempt_total 5553
telemt_upstream_connect_success_total 5524
telemt_upstream_connect_fail_total 14
telemt_upstream_connect_attempts_per_request{bucket="1"} 5524
telemt_upstream_connect_attempts_per_request{bucket="2"} 14
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3226
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2289
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 9
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 14
telemt_me_keepalive_timeout_total 78
telemt_me_reconnect_attempts_total 1216
telemt_me_reconnect_success_total 1225
telemt_me_reader_eof_total 1248
telemt_me_idle_close_by_peer_total 1248
telemt_me_route_drop_no_conn_total 57094
telemt_me_route_drop_channel_closed_total 1
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_single_endpoint_shadow_rotate_total 40
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 432
telemt_desync_full_logged_total 160
telemt_desync_suppressed_total 272
telemt_desync_frames_bucket_total{bucket="1_2"} 54
telemt_desync_frames_bucket_total{bucket="3_10"} 183
telemt_desync_frames_bucket_total{bucket="gt_10"} 195
telemt_pool_swap_total 2
telemt_pool_force_close_total 53
telemt_me_writer_removed_unexpected_total 1248
telemt_me_writer_restored_same_endpoint_total 1205
telemt_me_writer_removed_unexpected_minus_restored_total 43
telemt_user_connections_total{user="hello"} 136171
telemt_user_connections_current{user="hello"} 582
telemt_user_octets_from_client{user="hello"} 1523241468 (1.42 GB)
telemt_user_octets_to_client{user="hello"} 38013117048 (35.40 GB)
telemt_user_unique_ips_current{user="hello"} 53
```