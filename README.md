# Server Metrics 2026-03-06 13:41:51 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.4

telemt_uptime_seconds 11993.7 (3h 19m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 363337
telemt_connections_bad_total 1692
telemt_handshake_timeouts_total 1985
telemt_upstream_connect_attempt_total 5329
telemt_upstream_connect_success_total 5293
telemt_upstream_connect_fail_total 14
telemt_upstream_connect_attempts_per_request{bucket="1"} 5307
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2955
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2309
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 18
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 11
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 14
telemt_me_keepalive_timeout_total 52
telemt_me_reconnect_attempts_total 748
telemt_me_reconnect_success_total 741
telemt_me_reader_eof_total 779
telemt_me_idle_close_by_peer_total 779
telemt_me_route_drop_no_conn_total 118674
telemt_me_route_drop_channel_closed_total 1
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_single_endpoint_shadow_rotate_total 51
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_floor_mode_switch_all_total 2
telemt_me_floor_mode_switch_total{from="static",to="adaptive"} 1
telemt_me_floor_mode_switch_total{from="adaptive",to="static"} 1
telemt_desync_total 1975
telemt_desync_full_logged_total 471
telemt_desync_suppressed_total 1504
telemt_desync_frames_bucket_total{bucket="1_2"} 456
telemt_desync_frames_bucket_total{bucket="3_10"} 672
telemt_desync_frames_bucket_total{bucket="gt_10"} 847
telemt_pool_swap_total 2
telemt_pool_force_close_total 83
telemt_me_writer_removed_unexpected_total 779
telemt_me_writer_restored_same_endpoint_total 735
telemt_me_writer_removed_unexpected_minus_restored_total 44
telemt_user_connections_total{user="hello"} 298631
telemt_user_connections_current{user="hello"} 1192
telemt_user_octets_from_client{user="hello"} 5628856584 (5.24 GB)
telemt_user_octets_to_client{user="hello"} 125956227636 (117.31 GB)
telemt_user_unique_ips_current{user="hello"} 304
telemt_user_unique_ips_recent_window{user="hello"} 146
```

## server2

```
telemt 3.3.4

telemt_uptime_seconds 11993.4 (3h 19m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 135308
telemt_connections_bad_total 815
telemt_handshake_timeouts_total 4279
telemt_upstream_connect_attempt_total 5396
telemt_upstream_connect_success_total 5381
telemt_upstream_connect_fail_total 15
telemt_upstream_connect_attempts_per_request{bucket="1"} 5396
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2498
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2883
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 15
telemt_me_keepalive_timeout_total 75
telemt_me_reconnect_attempts_total 568
telemt_me_reconnect_success_total 561
telemt_me_reader_eof_total 599
telemt_me_idle_close_by_peer_total 599
telemt_me_route_drop_no_conn_total 60150
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_single_endpoint_shadow_rotate_total 51
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_floor_mode_switch_all_total 2
telemt_me_floor_mode_switch_total{from="static",to="adaptive"} 1
telemt_me_floor_mode_switch_total{from="adaptive",to="static"} 1
telemt_desync_total 451
telemt_desync_full_logged_total 158
telemt_desync_suppressed_total 293
telemt_desync_frames_bucket_total{bucket="1_2"} 74
telemt_desync_frames_bucket_total{bucket="3_10"} 164
telemt_desync_frames_bucket_total{bucket="gt_10"} 213
telemt_pool_swap_total 3
telemt_pool_force_close_total 94
telemt_me_writer_removed_unexpected_total 599
telemt_me_writer_restored_same_endpoint_total 561
telemt_me_writer_removed_unexpected_minus_restored_total 38
telemt_user_connections_total{user="hello"} 122900
telemt_user_connections_current{user="hello"} 497
telemt_user_octets_from_client{user="hello"} 1326170572 (1.24 GB)
telemt_user_octets_to_client{user="hello"} 58183312512 (54.19 GB)
telemt_user_unique_ips_current{user="hello"} 132
telemt_user_unique_ips_recent_window{user="hello"} 77
```

## server3

```
telemt 3.3.4

telemt_uptime_seconds 11993.4 (3h 19m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 286934
telemt_connections_bad_total 4839
telemt_handshake_timeouts_total 27600
telemt_upstream_connect_attempt_total 7203
telemt_upstream_connect_success_total 7165
telemt_upstream_connect_fail_total 31
telemt_upstream_connect_attempts_per_request{bucket="1"} 7196
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3830
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3321
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 14
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 31
telemt_me_keepalive_timeout_total 89
telemt_me_reconnect_attempts_total 1709
telemt_me_reconnect_success_total 1701
telemt_me_reader_eof_total 1788
telemt_me_idle_close_by_peer_total 1788
telemt_me_route_drop_no_conn_total 134390
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_single_endpoint_shadow_rotate_total 50
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_floor_mode_switch_all_total 2
telemt_me_floor_mode_switch_total{from="static",to="adaptive"} 1
telemt_me_floor_mode_switch_total{from="adaptive",to="static"} 1
telemt_desync_total 448
telemt_desync_full_logged_total 129
telemt_desync_suppressed_total 319
telemt_desync_frames_bucket_total{bucket="1_2"} 99
telemt_desync_frames_bucket_total{bucket="3_10"} 191
telemt_desync_frames_bucket_total{bucket="gt_10"} 158
telemt_pool_swap_total 1
telemt_pool_force_close_total 83
telemt_pool_stale_pick_total 381
telemt_me_writer_removed_unexpected_total 1789
telemt_me_writer_restored_same_endpoint_total 1696
telemt_me_writer_removed_unexpected_minus_restored_total 93
telemt_user_connections_total{user="hello"} 244602
telemt_user_connections_current{user="hello"} 745
telemt_user_octets_from_client{user="hello"} 2403019188 (2.24 GB)
telemt_user_octets_to_client{user="hello"} 78336616748 (72.96 GB)
telemt_user_unique_ips_current{user="hello"} 207
telemt_user_unique_ips_recent_window{user="hello"} 126
```

## server4

```
telemt 3.3.4

telemt_uptime_seconds 11309.6 (3h 8m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 164809
telemt_connections_bad_total 36886
telemt_handshake_timeouts_total 3022
telemt_upstream_connect_attempt_total 5641
telemt_upstream_connect_success_total 5641
telemt_upstream_connect_attempts_per_request{bucket="1"} 5641
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3255
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2386
telemt_me_keepalive_timeout_total 71
telemt_me_reconnect_attempts_total 760
telemt_me_reconnect_success_total 753
telemt_me_reader_eof_total 765
telemt_me_idle_close_by_peer_total 765
telemt_me_route_drop_no_conn_total 67325
telemt_me_route_drop_channel_closed_total 1
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_single_endpoint_shadow_rotate_total 49
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_floor_mode_switch_all_total 1
telemt_me_floor_mode_switch_total{from="static",to="adaptive"} 1
telemt_desync_total 206
telemt_desync_full_logged_total 74
telemt_desync_suppressed_total 132
telemt_desync_frames_bucket_total{bucket="1_2"} 58
telemt_desync_frames_bucket_total{bucket="3_10"} 78
telemt_desync_frames_bucket_total{bucket="gt_10"} 70
telemt_pool_swap_total 3
telemt_pool_force_close_total 135
telemt_me_writer_removed_unexpected_total 765
telemt_me_writer_restored_same_endpoint_total 753
telemt_me_writer_removed_unexpected_minus_restored_total 12
telemt_user_connections_total{user="hello"} 122351
telemt_user_connections_current{user="hello"} 540
telemt_user_octets_from_client{user="hello"} 1465186604 (1.36 GB)
telemt_user_octets_to_client{user="hello"} 49621820696 (46.21 GB)
telemt_user_unique_ips_current{user="hello"} 128
telemt_user_unique_ips_recent_window{user="hello"} 78
```

## server5

```
telemt 3.3.4

telemt_uptime_seconds 11993.7 (3h 19m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 220687
telemt_connections_bad_total 7764
telemt_handshake_timeouts_total 2417
telemt_upstream_connect_attempt_total 4253
telemt_upstream_connect_success_total 4246
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 4247
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2361
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1862
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 23
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_keepalive_timeout_total 57
telemt_me_reconnect_attempts_total 320
telemt_me_reconnect_success_total 312
telemt_me_reader_eof_total 320
telemt_me_idle_close_by_peer_total 320
telemt_me_route_drop_no_conn_total 114128
telemt_me_route_drop_channel_closed_total 3
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_single_endpoint_shadow_rotate_total 49
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_floor_mode_switch_all_total 2
telemt_me_floor_mode_switch_total{from="static",to="adaptive"} 1
telemt_me_floor_mode_switch_total{from="adaptive",to="static"} 1
telemt_desync_total 332
telemt_desync_full_logged_total 113
telemt_desync_suppressed_total 219
telemt_desync_frames_bucket_total{bucket="1_2"} 133
telemt_desync_frames_bucket_total{bucket="3_10"} 104
telemt_desync_frames_bucket_total{bucket="gt_10"} 95
telemt_pool_swap_total 3
telemt_pool_force_close_total 111
telemt_pool_stale_pick_total 160
telemt_me_writer_removed_unexpected_total 321
telemt_me_writer_restored_same_endpoint_total 311
telemt_me_writer_removed_unexpected_minus_restored_total 10
telemt_user_connections_total{user="hello"} 198829
telemt_user_connections_current{user="hello"} 524
telemt_user_octets_from_client{user="hello"} 13900801208 (12.95 GB)
telemt_user_octets_to_client{user="hello"} 113942640536 (106.12 GB)
telemt_user_unique_ips_current{user="hello"} 146
telemt_user_unique_ips_recent_window{user="hello"} 84
```