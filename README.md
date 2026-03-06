# Server Metrics 2026-03-06 20:02:29 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.5

telemt_uptime_seconds 6864.4 (1h 54m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 160713
telemt_connections_bad_total 1637
telemt_handshake_timeouts_total 6444
telemt_upstream_connect_attempt_total 10389
telemt_upstream_connect_success_total 10288
telemt_upstream_connect_fail_total 37
telemt_upstream_connect_attempts_per_request{bucket="1"} 10325
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3395
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6815
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 22
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 56
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 37
telemt_me_keepalive_timeout_total 317
telemt_me_reconnect_attempts_total 3332
telemt_me_reconnect_success_total 3316
telemt_me_reader_eof_total 4334
telemt_me_idle_close_by_peer_total 4334
telemt_me_route_drop_no_conn_total 63489
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_shadow_rotate_total 60
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 590
telemt_desync_full_logged_total 171
telemt_desync_suppressed_total 419
telemt_desync_frames_bucket_total{bucket="1_2"} 175
telemt_desync_frames_bucket_total{bucket="3_10"} 222
telemt_desync_frames_bucket_total{bucket="gt_10"} 193
telemt_pool_swap_total 2
telemt_pool_force_close_total 184
telemt_pool_stale_pick_total 151
telemt_me_writer_removed_unexpected_total 4358
telemt_me_writer_restored_same_endpoint_total 3310
telemt_me_writer_removed_unexpected_minus_restored_total 1048
telemt_user_connections_total{user="hello"} 140443
telemt_user_connections_current{user="hello"} 758
telemt_user_octets_from_client{user="hello"} 2226492468 (2.07 GB)
telemt_user_octets_to_client{user="hello"} 49260182296 (45.88 GB)
telemt_user_unique_ips_current{user="hello"} 213
telemt_user_unique_ips_recent_window{user="hello"} 103
```

## server2

```
telemt 3.3.5

telemt_uptime_seconds 6864.1 (1h 54m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 57910
telemt_connections_bad_total 51
telemt_handshake_timeouts_total 2446
telemt_upstream_connect_attempt_total 13079
telemt_upstream_connect_success_total 13078
telemt_upstream_connect_attempts_per_request{bucket="1"} 13078
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3291
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9781
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 6
telemt_me_keepalive_timeout_total 216
telemt_me_reconnect_attempts_total 4692
telemt_me_reconnect_success_total 4687
telemt_me_reader_eof_total 6343
telemt_me_idle_close_by_peer_total 6341
telemt_me_route_drop_no_conn_total 21129
telemt_me_single_endpoint_shadow_rotate_total 60
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 252
telemt_desync_full_logged_total 81
telemt_desync_suppressed_total 171
telemt_desync_frames_bucket_total{bucket="1_2"} 30
telemt_desync_frames_bucket_total{bucket="3_10"} 111
telemt_desync_frames_bucket_total{bucket="gt_10"} 111
telemt_pool_swap_total 2
telemt_pool_force_close_total 96
telemt_me_writer_removed_unexpected_total 6343
telemt_me_writer_restored_same_endpoint_total 4685
telemt_me_writer_removed_unexpected_minus_restored_total 1658
telemt_user_connections_total{user="hello"} 51348
telemt_user_connections_current{user="hello"} 375
telemt_user_octets_from_client{user="hello"} 1000419280 (954.07 MB)
telemt_user_octets_to_client{user="hello"} 15729921316 (14.65 GB)
telemt_user_unique_ips_current{user="hello"} 103
telemt_user_unique_ips_recent_window{user="hello"} 49
```

## server3

```
telemt 3.3.5

telemt_uptime_seconds 6864.0 (1h 54m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 110934
telemt_connections_bad_total 278
telemt_handshake_timeouts_total 1208
telemt_upstream_connect_attempt_total 8723
telemt_upstream_connect_success_total 8665
telemt_upstream_connect_fail_total 22
telemt_upstream_connect_attempts_per_request{bucket="1"} 8687
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3361
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5264
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 40
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 22
telemt_me_keepalive_timeout_total 532
telemt_me_reconnect_attempts_total 1888
telemt_me_reconnect_success_total 1878
telemt_me_reader_eof_total 2541
telemt_me_idle_close_by_peer_total 2540
telemt_me_route_drop_no_conn_total 39631
telemt_me_route_drop_channel_closed_total 1
telemt_me_single_endpoint_shadow_rotate_total 56
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 494
telemt_desync_full_logged_total 120
telemt_desync_suppressed_total 374
telemt_desync_frames_bucket_total{bucket="1_2"} 87
telemt_desync_frames_bucket_total{bucket="3_10"} 208
telemt_desync_frames_bucket_total{bucket="gt_10"} 199
telemt_pool_swap_total 4
telemt_pool_force_close_total 133
telemt_pool_stale_pick_total 116
telemt_me_writer_removed_unexpected_total 2597
telemt_me_writer_restored_same_endpoint_total 1871
telemt_me_writer_removed_unexpected_minus_restored_total 726
telemt_user_connections_total{user="hello"} 102370
telemt_user_connections_current{user="hello"} 434
telemt_user_octets_from_client{user="hello"} 4931145988 (4.59 GB)
telemt_user_octets_to_client{user="hello"} 28078014080 (26.15 GB)
telemt_user_unique_ips_current{user="hello"} 144
telemt_user_unique_ips_recent_window{user="hello"} 75
```

## server4

```
telemt 3.3.5

telemt_uptime_seconds 6864.6 (1h 54m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 126116
telemt_connections_bad_total 45552
telemt_handshake_timeouts_total 7999
telemt_upstream_connect_attempt_total 9807
telemt_upstream_connect_success_total 9774
telemt_upstream_connect_fail_total 15
telemt_upstream_connect_attempts_per_request{bucket="1"} 9789
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4967
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4787
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 20
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 15
telemt_me_keepalive_timeout_total 190
telemt_me_reconnect_attempts_total 2970
telemt_me_reconnect_success_total 2961
telemt_me_reader_eof_total 3767
telemt_me_idle_close_by_peer_total 3767
telemt_me_route_drop_no_conn_total 24955
telemt_me_single_endpoint_shadow_rotate_total 57
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 57
telemt_desync_full_logged_total 20
telemt_desync_suppressed_total 37
telemt_desync_frames_bucket_total{bucket="1_2"} 15
telemt_desync_frames_bucket_total{bucket="3_10"} 26
telemt_desync_frames_bucket_total{bucket="gt_10"} 16
telemt_pool_swap_total 3
telemt_pool_force_close_total 113
telemt_pool_stale_pick_total 449
telemt_me_writer_removed_unexpected_total 3769
telemt_me_writer_restored_same_endpoint_total 2957
telemt_me_writer_removed_unexpected_minus_restored_total 812
telemt_user_connections_total{user="hello"} 70192
telemt_user_connections_current{user="hello"} 414
telemt_user_octets_from_client{user="hello"} 1007758880 (961.07 MB)
telemt_user_octets_to_client{user="hello"} 24132287396 (22.47 GB)
telemt_user_unique_ips_current{user="hello"} 103
telemt_user_unique_ips_recent_window{user="hello"} 55
```

## server5

```
telemt 3.3.5

telemt_uptime_seconds 6863.0 (1h 54m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 96606
telemt_connections_bad_total 446
telemt_handshake_timeouts_total 521
telemt_upstream_connect_attempt_total 9709
telemt_upstream_connect_success_total 9657
telemt_upstream_connect_fail_total 12
telemt_upstream_connect_attempts_per_request{bucket="1"} 9669
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3778
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5802
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 75
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 12
telemt_me_keepalive_timeout_total 433
telemt_me_reconnect_attempts_total 2843
telemt_me_reconnect_success_total 2831
telemt_me_reader_eof_total 3842
telemt_me_idle_close_by_peer_total 3841
telemt_me_route_drop_no_conn_total 35709
telemt_me_route_drop_channel_closed_total 3
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_shadow_rotate_total 56
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 504
telemt_desync_full_logged_total 114
telemt_desync_suppressed_total 390
telemt_desync_frames_bucket_total{bucket="1_2"} 188
telemt_desync_frames_bucket_total{bucket="3_10"} 151
telemt_desync_frames_bucket_total{bucket="gt_10"} 165
telemt_pool_swap_total 3
telemt_pool_force_close_total 147
telemt_pool_stale_pick_total 78
telemt_me_writer_removed_unexpected_total 3878
telemt_me_writer_restored_same_endpoint_total 2829
telemt_me_writer_removed_unexpected_minus_restored_total 1049
telemt_user_connections_total{user="hello"} 91388
telemt_user_connections_current{user="hello"} 427
telemt_user_octets_from_client{user="hello"} 8485370612 (7.90 GB)
telemt_user_octets_to_client{user="hello"} 33964727644 (31.63 GB)
telemt_user_unique_ips_current{user="hello"} 112
telemt_user_unique_ips_recent_window{user="hello"} 58
```