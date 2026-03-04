# Server Metrics 2026-03-04 08:07:27 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.1.6

telemt_uptime_seconds 39408.8 (10h 56m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 449961
telemt_connections_bad_total 7963
telemt_handshake_timeouts_total 6276
telemt_upstream_connect_attempt_total 24420
telemt_upstream_connect_success_total 24308
telemt_upstream_connect_fail_total 50
telemt_upstream_connect_attempts_per_request{bucket="1"} 24308
telemt_upstream_connect_attempts_per_request{bucket="2"} 50
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13767
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10507
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 15
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 19
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 50
telemt_me_keepalive_timeout_total 258
telemt_me_reconnect_attempts_total 4787
telemt_me_reconnect_success_total 4754
telemt_me_reader_eof_total 4865
telemt_me_idle_close_by_peer_total 4865
telemt_me_route_drop_no_conn_total 151890
telemt_me_route_drop_channel_closed_total 1
telemt_me_hardswap_pending_ttl_expired_total 9
telemt_me_single_endpoint_shadow_rotate_total 156
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 840
telemt_desync_full_logged_total 310
telemt_desync_suppressed_total 530
telemt_desync_frames_bucket_total{bucket="1_2"} 241
telemt_desync_frames_bucket_total{bucket="3_10"} 307
telemt_desync_frames_bucket_total{bucket="gt_10"} 292
telemt_pool_swap_total 9
telemt_pool_force_close_total 347
telemt_me_writer_removed_unexpected_total 4865
telemt_me_writer_restored_same_endpoint_total 4733
telemt_me_writer_removed_unexpected_minus_restored_total 132
telemt_user_connections_total{user="hello"} 377731
telemt_user_connections_current{user="hello"} 920
telemt_user_octets_from_client{user="hello"} 4410774976 (4.11 GB)
telemt_user_octets_to_client{user="hello"} 112322218640 (104.61 GB)
telemt_user_unique_ips_current{user="hello"} 97
```

## server2

```
telemt 3.1.6

telemt_uptime_seconds 39405.5 (10h 56m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 188220
telemt_connections_bad_total 1713
telemt_handshake_timeouts_total 23688
telemt_upstream_connect_attempt_total 80371
telemt_upstream_connect_success_total 79187
telemt_upstream_connect_fail_total 554
telemt_upstream_connect_attempts_per_request{bucket="1"} 79181
telemt_upstream_connect_attempts_per_request{bucket="2"} 560
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 53676
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 25489
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 22
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 554
telemt_me_keepalive_timeout_total 1213
telemt_me_reconnect_attempts_total 46613
telemt_me_reconnect_success_total 46536
telemt_me_reader_eof_total 47684
telemt_me_idle_close_by_peer_total 47683
telemt_me_route_drop_no_conn_total 77876
telemt_me_hardswap_pending_ttl_expired_total 12
telemt_me_single_endpoint_outage_enter_total 2
telemt_me_single_endpoint_outage_exit_total 2
telemt_me_single_endpoint_outage_reconnect_attempt_total 37
telemt_me_single_endpoint_outage_reconnect_success_total 1
telemt_me_single_endpoint_quarantine_bypass_total 37
telemt_me_single_endpoint_shadow_rotate_total 169
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 376
telemt_desync_full_logged_total 135
telemt_desync_suppressed_total 241
telemt_desync_frames_bucket_total{bucket="1_2"} 83
telemt_desync_frames_bucket_total{bucket="3_10"} 185
telemt_desync_frames_bucket_total{bucket="gt_10"} 108
telemt_pool_swap_total 2
telemt_pool_force_close_total 138
telemt_pool_stale_pick_total 55
telemt_me_writer_removed_unexpected_total 47764
telemt_me_writer_restored_same_endpoint_total 46511
telemt_me_writer_removed_unexpected_minus_restored_total 1253
telemt_user_connections_total{user="hello"} 135540
telemt_user_connections_current{user="hello"} 394
telemt_user_octets_from_client{user="hello"} 1648013628 (1.53 GB)
telemt_user_octets_to_client{user="hello"} 52513188768 (48.91 GB)
telemt_user_unique_ips_current{user="hello"} 39
```

## server3

```
telemt 3.1.6

telemt_uptime_seconds 39404.2 (10h 56m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 379142
telemt_connections_bad_total 110803
telemt_handshake_timeouts_total 10979
telemt_upstream_connect_attempt_total 59905
telemt_upstream_connect_success_total 59559
telemt_upstream_connect_fail_total 164
telemt_upstream_connect_attempts_per_request{bucket="1"} 59558
telemt_upstream_connect_attempts_per_request{bucket="2"} 165
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 34012
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 25381
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 166
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 164
telemt_me_keepalive_timeout_total 799
telemt_me_reconnect_attempts_total 27711
telemt_me_reconnect_success_total 27640
telemt_me_reader_eof_total 29185
telemt_me_idle_close_by_peer_total 29182
telemt_me_route_drop_no_conn_total 117631
telemt_me_hardswap_pending_ttl_expired_total 11
telemt_me_single_endpoint_shadow_rotate_total 167
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 603
telemt_desync_full_logged_total 226
telemt_desync_suppressed_total 377
telemt_desync_frames_bucket_total{bucket="1_2"} 169
telemt_desync_frames_bucket_total{bucket="3_10"} 217
telemt_desync_frames_bucket_total{bucket="gt_10"} 217
telemt_pool_swap_total 4
telemt_pool_force_close_total 199
telemt_me_writer_removed_unexpected_total 29196
telemt_me_writer_restored_same_endpoint_total 27619
telemt_me_writer_removed_unexpected_minus_restored_total 1577
telemt_user_connections_total{user="hello"} 243525
telemt_user_connections_current{user="hello"} 546
telemt_user_octets_from_client{user="hello"} 2347413644 (2.19 GB)
telemt_user_octets_to_client{user="hello"} 90757463668 (84.52 GB)
telemt_user_unique_ips_current{user="hello"} 55
```

## server4

```
telemt 3.1.6

telemt_uptime_seconds 39403.0 (10h 56m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 214825
telemt_connections_bad_total 17565
telemt_handshake_timeouts_total 7868
telemt_upstream_connect_attempt_total 29645
telemt_upstream_connect_success_total 29520
telemt_upstream_connect_fail_total 61
telemt_upstream_connect_attempts_per_request{bucket="1"} 29520
telemt_upstream_connect_attempts_per_request{bucket="2"} 61
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 18301
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11218
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 61
telemt_me_keepalive_timeout_total 335
telemt_me_reconnect_attempts_total 6267
telemt_me_reconnect_success_total 6251
telemt_me_reader_eof_total 6370
telemt_me_idle_close_by_peer_total 6370
telemt_me_route_drop_no_conn_total 70170
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_single_endpoint_shadow_rotate_total 164
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 167
telemt_desync_full_logged_total 70
telemt_desync_suppressed_total 97
telemt_desync_frames_bucket_total{bucket="1_2"} 42
telemt_desync_frames_bucket_total{bucket="3_10"} 82
telemt_desync_frames_bucket_total{bucket="gt_10"} 43
telemt_pool_swap_total 11
telemt_pool_force_close_total 261
telemt_me_writer_removed_unexpected_total 6370
telemt_me_writer_restored_same_endpoint_total 6230
telemt_me_writer_removed_unexpected_minus_restored_total 140
telemt_user_connections_total{user="hello"} 170408
telemt_user_connections_current{user="hello"} 300
telemt_user_octets_from_client{user="hello"} 1753004448 (1.63 GB)
telemt_user_octets_to_client{user="hello"} 61073696672 (56.88 GB)
telemt_user_unique_ips_current{user="hello"} 34
```

## server5

```
telemt 3.1.6

telemt_uptime_seconds 39401.8 (10h 56m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 363768
telemt_connections_bad_total 6431
telemt_handshake_timeouts_total 131372
telemt_upstream_connect_attempt_total 57400
telemt_upstream_connect_success_total 57007
telemt_upstream_connect_fail_total 184
telemt_upstream_connect_attempts_per_request{bucket="1"} 57007
telemt_upstream_connect_attempts_per_request{bucket="2"} 184
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 34088
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 22767
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 150
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 184
telemt_me_keepalive_timeout_total 777
telemt_me_reconnect_attempts_total 26943
telemt_me_reconnect_success_total 26922
telemt_me_reader_eof_total 28333
telemt_me_idle_close_by_peer_total 28332
telemt_me_route_drop_no_conn_total 103201
telemt_me_route_drop_channel_closed_total 1
telemt_me_hardswap_pending_ttl_expired_total 12
telemt_me_single_endpoint_shadow_rotate_total 168
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 247
telemt_desync_full_logged_total 84
telemt_desync_suppressed_total 163
telemt_desync_frames_bucket_total{bucket="1_2"} 44
telemt_desync_frames_bucket_total{bucket="3_10"} 121
telemt_desync_frames_bucket_total{bucket="gt_10"} 82
telemt_pool_swap_total 4
telemt_pool_force_close_total 117
telemt_pool_stale_pick_total 2751
telemt_me_writer_removed_unexpected_total 28347
telemt_me_writer_restored_same_endpoint_total 26897
telemt_me_writer_removed_unexpected_minus_restored_total 1450
telemt_user_connections_total{user="hello"} 218350
telemt_user_connections_current{user="hello"} 418
telemt_user_octets_from_client{user="hello"} 2874606144 (2.68 GB)
telemt_user_octets_to_client{user="hello"} 54255489068 (50.53 GB)
telemt_user_unique_ips_current{user="hello"} 42
```