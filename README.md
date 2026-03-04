# Server Metrics 2026-03-04 06:30:06 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.1.6

telemt_uptime_seconds 33568.1 (9h 19m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 292084
telemt_connections_bad_total 3475
telemt_handshake_timeouts_total 5147
telemt_upstream_connect_attempt_total 22298
telemt_upstream_connect_success_total 22197
telemt_upstream_connect_fail_total 45
telemt_upstream_connect_attempts_per_request{bucket="1"} 22197
telemt_upstream_connect_attempts_per_request{bucket="2"} 45
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12596
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9569
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 13
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 19
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 45
telemt_me_keepalive_timeout_total 237
telemt_me_reconnect_attempts_total 4645
telemt_me_reconnect_success_total 4620
telemt_me_reader_eof_total 4729
telemt_me_idle_close_by_peer_total 4729
telemt_me_route_drop_no_conn_total 110435
telemt_me_route_drop_channel_closed_total 1
telemt_me_hardswap_pending_ttl_expired_total 8
telemt_me_single_endpoint_shadow_rotate_total 135
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 705
telemt_desync_full_logged_total 264
telemt_desync_suppressed_total 441
telemt_desync_frames_bucket_total{bucket="1_2"} 201
telemt_desync_frames_bucket_total{bucket="3_10"} 251
telemt_desync_frames_bucket_total{bucket="gt_10"} 253
telemt_pool_swap_total 8
telemt_pool_force_close_total 300
telemt_me_writer_removed_unexpected_total 4729
telemt_me_writer_restored_same_endpoint_total 4600
telemt_me_writer_removed_unexpected_minus_restored_total 129
telemt_user_connections_total{user="hello"} 272089
telemt_user_connections_current{user="hello"} 680
telemt_user_octets_from_client{user="hello"} 2855993268 (2.66 GB)
telemt_user_octets_to_client{user="hello"} 85713702576 (79.83 GB)
telemt_user_unique_ips_current{user="hello"} 123
```

## server2

```
telemt 3.1.6

telemt_uptime_seconds 33564.7 (9h 19m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 145655
telemt_connections_bad_total 960
telemt_handshake_timeouts_total 22208
telemt_upstream_connect_attempt_total 71849
telemt_upstream_connect_success_total 70955
telemt_upstream_connect_fail_total 425
telemt_upstream_connect_attempts_per_request{bucket="1"} 70949
telemt_upstream_connect_attempts_per_request{bucket="2"} 431
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 47854
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 23081
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 20
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 425
telemt_me_keepalive_timeout_total 1045
telemt_me_reconnect_attempts_total 42665
telemt_me_reconnect_success_total 42631
telemt_me_reader_eof_total 43702
telemt_me_idle_close_by_peer_total 43701
telemt_me_route_drop_no_conn_total 46786
telemt_me_hardswap_pending_ttl_expired_total 10
telemt_me_single_endpoint_shadow_rotate_total 145
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 268
telemt_desync_full_logged_total 97
telemt_desync_suppressed_total 171
telemt_desync_frames_bucket_total{bucket="1_2"} 66
telemt_desync_frames_bucket_total{bucket="3_10"} 142
telemt_desync_frames_bucket_total{bucket="gt_10"} 60
telemt_pool_swap_total 2
telemt_pool_force_close_total 138
telemt_pool_stale_pick_total 54
telemt_me_writer_removed_unexpected_total 43778
telemt_me_writer_restored_same_endpoint_total 42610
telemt_me_writer_removed_unexpected_minus_restored_total 1168
telemt_user_connections_total{user="hello"} 96219
telemt_user_connections_current{user="hello"} 305
telemt_user_octets_from_client{user="hello"} 946929624 (903.06 MB)
telemt_user_octets_to_client{user="hello"} 38665963752 (36.01 GB)
telemt_user_unique_ips_current{user="hello"} 37
```

## server3

```
telemt 3.1.6

telemt_uptime_seconds 33563.4 (9h 19m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 286276
telemt_connections_bad_total 95651
telemt_handshake_timeouts_total 7220
telemt_upstream_connect_attempt_total 46816
telemt_upstream_connect_success_total 46526
telemt_upstream_connect_fail_total 136
telemt_upstream_connect_attempts_per_request{bucket="1"} 46525
telemt_upstream_connect_attempts_per_request{bucket="2"} 137
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 26883
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 19511
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 132
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 136
telemt_me_keepalive_timeout_total 611
telemt_me_reconnect_attempts_total 19813
telemt_me_reconnect_success_total 19761
telemt_me_reader_eof_total 20864
telemt_me_idle_close_by_peer_total 20861
telemt_me_route_drop_no_conn_total 71084
telemt_me_hardswap_pending_ttl_expired_total 9
telemt_me_single_endpoint_shadow_rotate_total 144
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 437
telemt_desync_full_logged_total 162
telemt_desync_suppressed_total 275
telemt_desync_frames_bucket_total{bucket="1_2"} 116
telemt_desync_frames_bucket_total{bucket="3_10"} 164
telemt_desync_frames_bucket_total{bucket="gt_10"} 157
telemt_pool_swap_total 3
telemt_pool_force_close_total 113
telemt_me_writer_removed_unexpected_total 20872
telemt_me_writer_restored_same_endpoint_total 19740
telemt_me_writer_removed_unexpected_minus_restored_total 1132
telemt_user_connections_total{user="hello"} 174958
telemt_user_connections_current{user="hello"} 438
telemt_user_octets_from_client{user="hello"} 1378220772 (1.28 GB)
telemt_user_octets_to_client{user="hello"} 47045240340 (43.81 GB)
telemt_user_unique_ips_current{user="hello"} 54
```

## server4

```
telemt 3.1.6

telemt_uptime_seconds 33562.4 (9h 19m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 151442
telemt_connections_bad_total 12310
telemt_handshake_timeouts_total 3929
telemt_upstream_connect_attempt_total 26376
telemt_upstream_connect_success_total 26273
telemt_upstream_connect_fail_total 50
telemt_upstream_connect_attempts_per_request{bucket="1"} 26273
telemt_upstream_connect_attempts_per_request{bucket="2"} 50
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 16248
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10024
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 50
telemt_me_keepalive_timeout_total 285
telemt_me_reconnect_attempts_total 5943
telemt_me_reconnect_success_total 5933
telemt_me_reader_eof_total 6046
telemt_me_idle_close_by_peer_total 6046
telemt_me_route_drop_no_conn_total 45243
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_single_endpoint_shadow_rotate_total 143
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 146
telemt_desync_full_logged_total 65
telemt_desync_suppressed_total 81
telemt_desync_frames_bucket_total{bucket="1_2"} 33
telemt_desync_frames_bucket_total{bucket="3_10"} 75
telemt_desync_frames_bucket_total{bucket="gt_10"} 38
telemt_pool_swap_total 9
telemt_pool_force_close_total 213
telemt_me_writer_removed_unexpected_total 6046
telemt_me_writer_restored_same_endpoint_total 5912
telemt_me_writer_removed_unexpected_minus_restored_total 134
telemt_user_connections_total{user="hello"} 127069
telemt_user_connections_current{user="hello"} 264
telemt_user_octets_from_client{user="hello"} 1261867560 (1.18 GB)
telemt_user_octets_to_client{user="hello"} 47425366492 (44.17 GB)
telemt_user_unique_ips_current{user="hello"} 38
```

## server5

```
telemt 3.1.6

telemt_uptime_seconds 33561.1 (9h 19m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 296688
telemt_connections_bad_total 6395
telemt_handshake_timeouts_total 127484
telemt_upstream_connect_attempt_total 46978
telemt_upstream_connect_success_total 46647
telemt_upstream_connect_fail_total 155
telemt_upstream_connect_attempts_per_request{bucket="1"} 46647
telemt_upstream_connect_attempts_per_request{bucket="2"} 155
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 27776
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 18751
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 118
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 155
telemt_me_keepalive_timeout_total 634
telemt_me_reconnect_attempts_total 21809
telemt_me_reconnect_success_total 21796
telemt_me_reader_eof_total 22989
telemt_me_idle_close_by_peer_total 22988
telemt_me_route_drop_no_conn_total 72319
telemt_me_route_drop_channel_closed_total 1
telemt_me_hardswap_pending_ttl_expired_total 10
telemt_me_single_endpoint_shadow_rotate_total 142
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 202
telemt_desync_full_logged_total 65
telemt_desync_suppressed_total 137
telemt_desync_frames_bucket_total{bucket="1_2"} 32
telemt_desync_frames_bucket_total{bucket="3_10"} 107
telemt_desync_frames_bucket_total{bucket="gt_10"} 63
telemt_pool_swap_total 4
telemt_pool_force_close_total 114
telemt_pool_stale_pick_total 2751
telemt_me_writer_removed_unexpected_total 23002
telemt_me_writer_restored_same_endpoint_total 21771
telemt_me_writer_removed_unexpected_minus_restored_total 1231
telemt_user_connections_total{user="hello"} 157608
telemt_user_connections_current{user="hello"} 336
telemt_user_octets_from_client{user="hello"} 2232092288 (2.08 GB)
telemt_user_octets_to_client{user="hello"} 36451598924 (33.95 GB)
telemt_user_unique_ips_current{user="hello"} 43
```