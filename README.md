# Server Metrics 2026-03-04 11:32:27 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.1.6

telemt_uptime_seconds 51709.2 (14h 21m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 830091
telemt_connections_bad_total 12013
telemt_handshake_timeouts_total 11463
telemt_upstream_connect_attempt_total 32333
telemt_upstream_connect_success_total 32196
telemt_upstream_connect_fail_total 58
telemt_upstream_connect_attempts_per_request{bucket="1"} 32196
telemt_upstream_connect_attempts_per_request{bucket="2"} 58
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 17804
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14343
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 25
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 24
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 58
telemt_me_keepalive_timeout_total 360
telemt_me_reconnect_attempts_total 7082
telemt_me_reconnect_success_total 7036
telemt_me_reader_eof_total 7255
telemt_me_idle_close_by_peer_total 7255
telemt_me_route_drop_no_conn_total 319129
telemt_me_route_drop_channel_closed_total 2
telemt_me_hardswap_pending_ttl_expired_total 12
telemt_me_single_endpoint_shadow_rotate_total 203
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 1353
telemt_desync_full_logged_total 459
telemt_desync_suppressed_total 894
telemt_desync_frames_bucket_total{bucket="1_2"} 378
telemt_desync_frames_bucket_total{bucket="3_10"} 525
telemt_desync_frames_bucket_total{bucket="gt_10"} 450
telemt_pool_swap_total 13
telemt_pool_force_close_total 524
telemt_pool_stale_pick_total 76
telemt_me_writer_removed_unexpected_total 7255
telemt_me_writer_restored_same_endpoint_total 7015
telemt_me_writer_removed_unexpected_minus_restored_total 240
telemt_user_connections_total{user="hello"} 671359
telemt_user_connections_current{user="hello"} 975
telemt_user_octets_from_client{user="hello"} 7337335152 (6.83 GB)
telemt_user_octets_to_client{user="hello"} 203692348292 (189.70 GB)
telemt_user_unique_ips_current{user="hello"} 108
```

## server2

```
telemt 3.1.6

telemt_uptime_seconds 51705.6 (14h 21m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 331008
telemt_connections_bad_total 2926
telemt_handshake_timeouts_total 27297
telemt_upstream_connect_attempt_total 99669
telemt_upstream_connect_success_total 98148
telemt_upstream_connect_fail_total 722
telemt_upstream_connect_attempts_per_request{bucket="1"} 98142
telemt_upstream_connect_attempts_per_request{bucket="2"} 728
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 65741
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 32384
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 23
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 722
telemt_me_keepalive_timeout_total 1380
telemt_me_reconnect_attempts_total 56327
telemt_me_reconnect_success_total 56239
telemt_me_reader_eof_total 57668
telemt_me_idle_close_by_peer_total 57667
telemt_me_route_drop_no_conn_total 140652
telemt_me_hardswap_pending_ttl_expired_total 16
telemt_me_single_endpoint_outage_enter_total 2
telemt_me_single_endpoint_outage_exit_total 2
telemt_me_single_endpoint_outage_reconnect_attempt_total 37
telemt_me_single_endpoint_outage_reconnect_success_total 1
telemt_me_single_endpoint_quarantine_bypass_total 37
telemt_me_single_endpoint_shadow_rotate_total 219
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 621
telemt_desync_full_logged_total 216
telemt_desync_suppressed_total 405
telemt_desync_frames_bucket_total{bucket="1_2"} 127
telemt_desync_frames_bucket_total{bucket="3_10"} 270
telemt_desync_frames_bucket_total{bucket="gt_10"} 224
telemt_pool_swap_total 3
telemt_pool_force_close_total 216
telemt_pool_stale_pick_total 56
telemt_me_writer_removed_unexpected_total 57748
telemt_me_writer_restored_same_endpoint_total 56214
telemt_me_writer_removed_unexpected_minus_restored_total 1534
telemt_user_connections_total{user="hello"} 251098
telemt_user_connections_current{user="hello"} 364
telemt_user_octets_from_client{user="hello"} 3283868692 (3.06 GB)
telemt_user_octets_to_client{user="hello"} 80425942176 (74.90 GB)
telemt_user_unique_ips_current{user="hello"} 37
```

## server3

```
telemt 3.1.6

telemt_uptime_seconds 51704.5 (14h 21m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 635576
telemt_connections_bad_total 155284
telemt_handshake_timeouts_total 19819
telemt_upstream_connect_attempt_total 78351
telemt_upstream_connect_success_total 77902
telemt_upstream_connect_fail_total 215
telemt_upstream_connect_attempts_per_request{bucket="1"} 77901
telemt_upstream_connect_attempts_per_request{bucket="2"} 216
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 45654
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 32032
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 216
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 215
telemt_me_keepalive_timeout_total 1021
telemt_me_reconnect_attempts_total 36930
telemt_me_reconnect_success_total 36840
telemt_me_reader_eof_total 38810
telemt_me_idle_close_by_peer_total 38806
telemt_me_route_drop_no_conn_total 240043
telemt_me_hardswap_pending_ttl_expired_total 15
telemt_me_single_endpoint_shadow_rotate_total 216
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 1131
telemt_desync_full_logged_total 403
telemt_desync_suppressed_total 728
telemt_desync_frames_bucket_total{bucket="1_2"} 342
telemt_desync_frames_bucket_total{bucket="3_10"} 376
telemt_desync_frames_bucket_total{bucket="gt_10"} 413
telemt_pool_swap_total 5
telemt_pool_force_close_total 294
telemt_me_writer_removed_unexpected_total 38822
telemt_me_writer_restored_same_endpoint_total 36819
telemt_me_writer_removed_unexpected_minus_restored_total 2003
telemt_user_connections_total{user="hello"} 441173
telemt_user_connections_current{user="hello"} 508
telemt_user_octets_from_client{user="hello"} 5843233768 (5.44 GB)
telemt_user_octets_to_client{user="hello"} 147582986420 (137.45 GB)
telemt_user_unique_ips_current{user="hello"} 80
```

## server4

```
telemt 3.1.6

telemt_uptime_seconds 51703.6 (14h 21m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 412682
telemt_connections_bad_total 28643
telemt_handshake_timeouts_total 66559
telemt_upstream_connect_attempt_total 38294
telemt_upstream_connect_success_total 38141
telemt_upstream_connect_fail_total 75
telemt_upstream_connect_attempts_per_request{bucket="1"} 38141
telemt_upstream_connect_attempts_per_request{bucket="2"} 75
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 23635
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14505
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 75
telemt_me_keepalive_timeout_total 428
telemt_me_reconnect_attempts_total 8217
telemt_me_reconnect_success_total 8189
telemt_me_reader_eof_total 8372
telemt_me_idle_close_by_peer_total 8372
telemt_me_route_drop_no_conn_total 117610
telemt_me_route_drop_channel_closed_total 1
telemt_me_hardswap_pending_ttl_expired_total 10
telemt_me_single_endpoint_shadow_rotate_total 213
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 232
telemt_desync_full_logged_total 97
telemt_desync_suppressed_total 135
telemt_desync_frames_bucket_total{bucket="1_2"} 56
telemt_desync_frames_bucket_total{bucket="3_10"} 98
telemt_desync_frames_bucket_total{bucket="gt_10"} 78
telemt_pool_swap_total 14
telemt_pool_force_close_total 375
telemt_me_writer_removed_unexpected_total 8372
telemt_me_writer_restored_same_endpoint_total 8168
telemt_me_writer_removed_unexpected_minus_restored_total 204
telemt_user_connections_total{user="hello"} 295186
telemt_user_connections_current{user="hello"} 459
telemt_user_octets_from_client{user="hello"} 3623193716 (3.37 GB)
telemt_user_octets_to_client{user="hello"} 110139071956 (102.58 GB)
telemt_user_unique_ips_current{user="hello"} 46
```

## server5

```
telemt 3.1.6

telemt_uptime_seconds 51702.2 (14h 21m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 555664
telemt_connections_bad_total 6816
telemt_handshake_timeouts_total 132446
telemt_upstream_connect_attempt_total 73488
telemt_upstream_connect_success_total 72983
telemt_upstream_connect_fail_total 240
telemt_upstream_connect_attempts_per_request{bucket="1"} 72983
telemt_upstream_connect_attempts_per_request{bucket="2"} 240
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 44022
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 28763
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 196
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 240
telemt_me_keepalive_timeout_total 957
telemt_me_reconnect_attempts_total 35368
telemt_me_reconnect_success_total 35335
telemt_me_reader_eof_total 37063
telemt_me_idle_close_by_peer_total 37062
telemt_me_route_drop_no_conn_total 177262
telemt_me_route_drop_channel_closed_total 1
telemt_me_hardswap_pending_ttl_expired_total 15
telemt_me_single_endpoint_shadow_rotate_total 218
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 800
telemt_desync_full_logged_total 251
telemt_desync_suppressed_total 549
telemt_desync_frames_bucket_total{bucket="1_2"} 144
telemt_desync_frames_bucket_total{bucket="3_10"} 340
telemt_desync_frames_bucket_total{bucket="gt_10"} 316
telemt_pool_swap_total 6
telemt_pool_force_close_total 263
telemt_pool_stale_pick_total 2870
telemt_me_writer_removed_unexpected_total 37075
telemt_me_writer_restored_same_endpoint_total 35310
telemt_me_writer_removed_unexpected_minus_restored_total 1765
telemt_user_connections_total{user="hello"} 391641
telemt_user_connections_current{user="hello"} 629
telemt_user_octets_from_client{user="hello"} 5110236604 (4.76 GB)
telemt_user_octets_to_client{user="hello"} 106570691824 (99.25 GB)
telemt_user_connections_total{user="hello2"} 1
telemt_user_octets_from_client{user="hello2"} 140 (140 B)
telemt_user_octets_to_client{user="hello2"} 104 (104 B)
telemt_user_unique_ips_current{user="hello"} 39
```