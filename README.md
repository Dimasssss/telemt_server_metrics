# Server Metrics 2026-03-04 04:47:28 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.1.6

telemt_uptime_seconds 27410.2 (7h 36m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 190173
telemt_connections_bad_total 1636
telemt_handshake_timeouts_total 3644
telemt_upstream_connect_attempt_total 19775
telemt_upstream_connect_success_total 19687
telemt_upstream_connect_fail_total 39
telemt_upstream_connect_attempts_per_request{bucket="1"} 19687
telemt_upstream_connect_attempts_per_request{bucket="2"} 39
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11149
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8512
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 11
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 15
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 39
telemt_me_keepalive_timeout_total 210
telemt_me_reconnect_attempts_total 4517
telemt_me_reconnect_success_total 4500
telemt_me_reader_eof_total 4605
telemt_me_idle_close_by_peer_total 4605
telemt_me_route_drop_no_conn_total 62599
telemt_me_route_drop_channel_closed_total 1
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_single_endpoint_shadow_rotate_total 111
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 518
telemt_desync_full_logged_total 183
telemt_desync_suppressed_total 335
telemt_desync_frames_bucket_total{bucket="1_2"} 137
telemt_desync_frames_bucket_total{bucket="3_10"} 178
telemt_desync_frames_bucket_total{bucket="gt_10"} 203
telemt_pool_swap_total 6
telemt_pool_force_close_total 218
telemt_me_writer_removed_unexpected_total 4605
telemt_me_writer_restored_same_endpoint_total 4480
telemt_me_writer_removed_unexpected_minus_restored_total 125
telemt_user_connections_total{user="hello"} 180251
telemt_user_connections_current{user="hello"} 571
telemt_user_octets_from_client{user="hello"} 1915956300 (1.78 GB)
telemt_user_octets_to_client{user="hello"} 57690715176 (53.73 GB)
telemt_user_unique_ips_current{user="hello"} 95
```

## server2

```
telemt 3.1.6

telemt_uptime_seconds 27406.6 (7h 36m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 88803
telemt_connections_bad_total 350
telemt_handshake_timeouts_total 20750
telemt_upstream_connect_attempt_total 63301
telemt_upstream_connect_success_total 62635
telemt_upstream_connect_fail_total 317
telemt_upstream_connect_attempts_per_request{bucket="1"} 62629
telemt_upstream_connect_attempts_per_request{bucket="2"} 323
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 42627
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 19988
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 20
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 317
telemt_me_keepalive_timeout_total 968
telemt_me_reconnect_attempts_total 38980
telemt_me_reconnect_success_total 38952
telemt_me_reader_eof_total 39939
telemt_me_idle_close_by_peer_total 39938
telemt_me_route_drop_no_conn_total 27973
telemt_me_hardswap_pending_ttl_expired_total 9
telemt_me_single_endpoint_shadow_rotate_total 120
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 194
telemt_desync_full_logged_total 80
telemt_desync_suppressed_total 114
telemt_desync_frames_bucket_total{bucket="1_2"} 42
telemt_desync_frames_bucket_total{bucket="3_10"} 102
telemt_desync_frames_bucket_total{bucket="gt_10"} 50
telemt_pool_swap_total 1
telemt_pool_force_close_total 75
telemt_me_writer_removed_unexpected_total 40000
telemt_me_writer_restored_same_endpoint_total 38931
telemt_me_writer_removed_unexpected_minus_restored_total 1069
telemt_user_connections_total{user="hello"} 65235
telemt_user_connections_current{user="hello"} 248
telemt_user_octets_from_client{user="hello"} 606559900 (578.46 MB)
telemt_user_octets_to_client{user="hello"} 29212897956 (27.21 GB)
telemt_user_unique_ips_current{user="hello"} 28
```

## server3

```
telemt 3.1.6

telemt_uptime_seconds 27405.3 (7h 36m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 201573
telemt_connections_bad_total 73448
telemt_handshake_timeouts_total 4333
telemt_upstream_connect_attempt_total 35606
telemt_upstream_connect_success_total 35363
telemt_upstream_connect_fail_total 113
telemt_upstream_connect_attempts_per_request{bucket="1"} 35363
telemt_upstream_connect_attempts_per_request{bucket="2"} 113
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 20833
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14418
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 112
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 113
telemt_me_keepalive_timeout_total 471
telemt_me_reconnect_attempts_total 14276
telemt_me_reconnect_success_total 14239
telemt_me_reader_eof_total 14980
telemt_me_idle_close_by_peer_total 14977
telemt_me_route_drop_no_conn_total 40385
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_single_endpoint_shadow_rotate_total 117
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 314
telemt_desync_full_logged_total 111
telemt_desync_suppressed_total 203
telemt_desync_frames_bucket_total{bucket="1_2"} 71
telemt_desync_frames_bucket_total{bucket="3_10"} 113
telemt_desync_frames_bucket_total{bucket="gt_10"} 130
telemt_pool_swap_total 3
telemt_pool_force_close_total 113
telemt_me_writer_removed_unexpected_total 14988
telemt_me_writer_restored_same_endpoint_total 14218
telemt_me_writer_removed_unexpected_minus_restored_total 770
telemt_user_connections_total{user="hello"} 119677
telemt_user_connections_current{user="hello"} 336
telemt_user_octets_from_client{user="hello"} 763549152 (728.18 MB)
telemt_user_octets_to_client{user="hello"} 30916294060 (28.79 GB)
telemt_user_unique_ips_current{user="hello"} 42
```

## server4

```
telemt 3.1.6

telemt_uptime_seconds 27404.3 (7h 36m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 100976
telemt_connections_bad_total 5428
telemt_handshake_timeouts_total 1148
telemt_upstream_connect_attempt_total 18601
telemt_upstream_connect_success_total 18520
telemt_upstream_connect_fail_total 40
telemt_upstream_connect_attempts_per_request{bucket="1"} 18520
telemt_upstream_connect_attempts_per_request{bucket="2"} 40
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11487
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7032
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 40
telemt_me_keepalive_timeout_total 196
telemt_me_reconnect_attempts_total 2902
telemt_me_reconnect_success_total 2901
telemt_me_reader_eof_total 2924
telemt_me_idle_close_by_peer_total 2924
telemt_me_route_drop_no_conn_total 32601
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_single_endpoint_shadow_rotate_total 115
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 113
telemt_desync_full_logged_total 48
telemt_desync_suppressed_total 65
telemt_desync_frames_bucket_total{bucket="1_2"} 25
telemt_desync_frames_bucket_total{bucket="3_10"} 61
telemt_desync_frames_bucket_total{bucket="gt_10"} 27
telemt_pool_swap_total 8
telemt_pool_force_close_total 184
telemt_me_writer_removed_unexpected_total 2924
telemt_me_writer_restored_same_endpoint_total 2880
telemt_me_writer_removed_unexpected_minus_restored_total 44
telemt_user_connections_total{user="hello"} 90017
telemt_user_connections_current{user="hello"} 213
telemt_user_octets_from_client{user="hello"} 758063452 (722.95 MB)
telemt_user_octets_to_client{user="hello"} 30422334692 (28.33 GB)
telemt_user_unique_ips_current{user="hello"} 33
```

## server5

```
telemt 3.1.6

telemt_uptime_seconds 27403.0 (7h 36m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 219970
telemt_connections_bad_total 4804
telemt_handshake_timeouts_total 99823
telemt_upstream_connect_attempt_total 40315
telemt_upstream_connect_success_total 40034
telemt_upstream_connect_fail_total 131
telemt_upstream_connect_attempts_per_request{bucket="1"} 40034
telemt_upstream_connect_attempts_per_request{bucket="2"} 131
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 23613
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 16318
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 101
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 131
telemt_me_keepalive_timeout_total 555
telemt_me_reconnect_attempts_total 19600
telemt_me_reconnect_success_total 19592
telemt_me_reader_eof_total 20719
telemt_me_idle_close_by_peer_total 20718
telemt_me_route_drop_no_conn_total 51938
telemt_me_route_drop_channel_closed_total 1
telemt_me_hardswap_pending_ttl_expired_total 8
telemt_me_single_endpoint_shadow_rotate_total 118
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 158
telemt_desync_full_logged_total 47
telemt_desync_suppressed_total 111
telemt_desync_frames_bucket_total{bucket="1_2"} 24
telemt_desync_frames_bucket_total{bucket="3_10"} 82
telemt_desync_frames_bucket_total{bucket="gt_10"} 52
telemt_pool_swap_total 3
telemt_pool_force_close_total 87
telemt_pool_stale_pick_total 2751
telemt_me_writer_removed_unexpected_total 20731
telemt_me_writer_restored_same_endpoint_total 19568
telemt_me_writer_removed_unexpected_minus_restored_total 1163
telemt_user_connections_total{user="hello"} 111464
telemt_user_connections_current{user="hello"} 223
telemt_user_octets_from_client{user="hello"} 781150604 (744.96 MB)
telemt_user_octets_to_client{user="hello"} 26009899384 (24.22 GB)
telemt_user_unique_ips_current{user="hello"} 26
```