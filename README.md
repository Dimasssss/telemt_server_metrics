# Server Metrics 2026-03-04 11:01:44 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.1.6

telemt_uptime_seconds 49865.5 (13h 51m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 778896
telemt_connections_bad_total 11431
telemt_handshake_timeouts_total 9701
telemt_upstream_connect_attempt_total 31859
telemt_upstream_connect_success_total 31725
telemt_upstream_connect_fail_total 57
telemt_upstream_connect_attempts_per_request{bucket="1"} 31725
telemt_upstream_connect_attempts_per_request{bucket="2"} 57
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 17531
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14145
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 25
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 24
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 57
telemt_me_keepalive_timeout_total 353
telemt_me_reconnect_attempts_total 7076
telemt_me_reconnect_success_total 7031
telemt_me_reader_eof_total 7250
telemt_me_idle_close_by_peer_total 7250
telemt_me_route_drop_no_conn_total 303623
telemt_me_route_drop_channel_closed_total 2
telemt_me_hardswap_pending_ttl_expired_total 12
telemt_me_single_endpoint_shadow_rotate_total 197
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 1273
telemt_desync_full_logged_total 434
telemt_desync_suppressed_total 839
telemt_desync_frames_bucket_total{bucket="1_2"} 350
telemt_desync_frames_bucket_total{bucket="3_10"} 489
telemt_desync_frames_bucket_total{bucket="gt_10"} 434
telemt_pool_swap_total 12
telemt_pool_force_close_total 492
telemt_pool_stale_pick_total 25
telemt_me_writer_removed_unexpected_total 7250
telemt_me_writer_restored_same_endpoint_total 7010
telemt_me_writer_removed_unexpected_minus_restored_total 240
telemt_user_connections_total{user="hello"} 632670
telemt_user_connections_current{user="hello"} 964
telemt_user_octets_from_client{user="hello"} 7012404660 (6.53 GB)
telemt_user_octets_to_client{user="hello"} 190949926616 (177.84 GB)
telemt_user_unique_ips_current{user="hello"} 117
```

## server2

```
telemt 3.1.6

telemt_uptime_seconds 49862.4 (13h 51m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 304417
telemt_connections_bad_total 2784
telemt_handshake_timeouts_total 27035
telemt_upstream_connect_attempt_total 96517
telemt_upstream_connect_success_total 95083
telemt_upstream_connect_fail_total 678
telemt_upstream_connect_attempts_per_request{bucket="1"} 95077
telemt_upstream_connect_attempts_per_request{bucket="2"} 684
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 63719
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 31342
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 22
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 678
telemt_me_keepalive_timeout_total 1362
telemt_me_reconnect_attempts_total 54862
telemt_me_reconnect_success_total 54776
telemt_me_reader_eof_total 56183
telemt_me_idle_close_by_peer_total 56182
telemt_me_route_drop_no_conn_total 134364
telemt_me_hardswap_pending_ttl_expired_total 15
telemt_me_single_endpoint_outage_enter_total 2
telemt_me_single_endpoint_outage_exit_total 2
telemt_me_single_endpoint_outage_reconnect_attempt_total 37
telemt_me_single_endpoint_outage_reconnect_success_total 1
telemt_me_single_endpoint_quarantine_bypass_total 37
telemt_me_single_endpoint_shadow_rotate_total 211
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 584
telemt_desync_full_logged_total 206
telemt_desync_suppressed_total 378
telemt_desync_frames_bucket_total{bucket="1_2"} 115
telemt_desync_frames_bucket_total{bucket="3_10"} 257
telemt_desync_frames_bucket_total{bucket="gt_10"} 212
telemt_pool_swap_total 3
telemt_pool_force_close_total 216
telemt_pool_stale_pick_total 56
telemt_me_writer_removed_unexpected_total 56263
telemt_me_writer_restored_same_endpoint_total 54751
telemt_me_writer_removed_unexpected_minus_restored_total 1512
telemt_user_connections_total{user="hello"} 235662
telemt_user_connections_current{user="hello"} 441
telemt_user_octets_from_client{user="hello"} 2801279956 (2.61 GB)
telemt_user_octets_to_client{user="hello"} 77201090776 (71.90 GB)
telemt_user_unique_ips_current{user="hello"} 48
```

## server3

```
telemt 3.1.6

telemt_uptime_seconds 49861.1 (13h 51m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 599807
telemt_connections_bad_total 150527
telemt_handshake_timeouts_total 18210
telemt_upstream_connect_attempt_total 74651
telemt_upstream_connect_success_total 74210
telemt_upstream_connect_fail_total 211
telemt_upstream_connect_attempts_per_request{bucket="1"} 74209
telemt_upstream_connect_attempts_per_request{bucket="2"} 212
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 43395
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 30605
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 210
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 211
telemt_me_keepalive_timeout_total 961
telemt_me_reconnect_attempts_total 34827
telemt_me_reconnect_success_total 34739
telemt_me_reader_eof_total 36620
telemt_me_idle_close_by_peer_total 36616
telemt_me_route_drop_no_conn_total 220854
telemt_me_hardswap_pending_ttl_expired_total 14
telemt_me_single_endpoint_shadow_rotate_total 209
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 1039
telemt_desync_full_logged_total 378
telemt_desync_suppressed_total 661
telemt_desync_frames_bucket_total{bucket="1_2"} 325
telemt_desync_frames_bucket_total{bucket="3_10"} 339
telemt_desync_frames_bucket_total{bucket="gt_10"} 375
telemt_pool_swap_total 4
telemt_pool_force_close_total 201
telemt_me_writer_removed_unexpected_total 36632
telemt_me_writer_restored_same_endpoint_total 34718
telemt_me_writer_removed_unexpected_minus_restored_total 1914
telemt_user_connections_total{user="hello"} 412245
telemt_user_connections_current{user="hello"} 729
telemt_user_octets_from_client{user="hello"} 5221733004 (4.86 GB)
telemt_user_octets_to_client{user="hello"} 139421182508 (129.85 GB)
telemt_user_unique_ips_current{user="hello"} 75
```

## server4

```
telemt 3.1.6

telemt_uptime_seconds 49860.3 (13h 51m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 391953
telemt_connections_bad_total 26977
telemt_handshake_timeouts_total 66196
telemt_upstream_connect_attempt_total 36892
telemt_upstream_connect_success_total 36745
telemt_upstream_connect_fail_total 72
telemt_upstream_connect_attempts_per_request{bucket="1"} 36745
telemt_upstream_connect_attempts_per_request{bucket="2"} 72
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 22821
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13923
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 72
telemt_me_keepalive_timeout_total 413
telemt_me_reconnect_attempts_total 7715
telemt_me_reconnect_success_total 7689
telemt_me_reader_eof_total 7850
telemt_me_idle_close_by_peer_total 7850
telemt_me_route_drop_no_conn_total 110271
telemt_me_route_drop_channel_closed_total 1
telemt_me_hardswap_pending_ttl_expired_total 9
telemt_me_single_endpoint_shadow_rotate_total 207
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 211
telemt_desync_full_logged_total 87
telemt_desync_suppressed_total 124
telemt_desync_frames_bucket_total{bucket="1_2"} 51
telemt_desync_frames_bucket_total{bucket="3_10"} 94
telemt_desync_frames_bucket_total{bucket="gt_10"} 66
telemt_pool_swap_total 13
telemt_pool_force_close_total 316
telemt_me_writer_removed_unexpected_total 7850
telemt_me_writer_restored_same_endpoint_total 7668
telemt_me_writer_removed_unexpected_minus_restored_total 182
telemt_user_connections_total{user="hello"} 276833
telemt_user_connections_current{user="hello"} 487
telemt_user_octets_from_client{user="hello"} 3299989352 (3.07 GB)
telemt_user_octets_to_client{user="hello"} 99751020036 (92.90 GB)
telemt_user_unique_ips_current{user="hello"} 49
```

## server5

```
telemt 3.1.6

telemt_uptime_seconds 49858.9 (13h 50m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 529074
telemt_connections_bad_total 6813
telemt_handshake_timeouts_total 132386
telemt_upstream_connect_attempt_total 71044
telemt_upstream_connect_success_total 70559
telemt_upstream_connect_fail_total 230
telemt_upstream_connect_attempts_per_request{bucket="1"} 70559
telemt_upstream_connect_attempts_per_request{bucket="2"} 230
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 42570
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 27796
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 191
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 230
telemt_me_keepalive_timeout_total 924
telemt_me_reconnect_attempts_total 34286
telemt_me_reconnect_success_total 34254
telemt_me_reader_eof_total 35948
telemt_me_idle_close_by_peer_total 35947
telemt_me_route_drop_no_conn_total 165900
telemt_me_route_drop_channel_closed_total 1
telemt_me_hardswap_pending_ttl_expired_total 14
telemt_me_single_endpoint_shadow_rotate_total 211
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 630
telemt_desync_full_logged_total 207
telemt_desync_suppressed_total 423
telemt_desync_frames_bucket_total{bucket="1_2"} 122
telemt_desync_frames_bucket_total{bucket="3_10"} 279
telemt_desync_frames_bucket_total{bucket="gt_10"} 229
telemt_pool_swap_total 6
telemt_pool_force_close_total 263
telemt_pool_stale_pick_total 2870
telemt_me_writer_removed_unexpected_total 35960
telemt_me_writer_restored_same_endpoint_total 34229
telemt_me_writer_removed_unexpected_minus_restored_total 1731
telemt_user_connections_total{user="hello"} 365829
telemt_user_connections_current{user="hello"} 566
telemt_user_octets_from_client{user="hello"} 4799492868 (4.47 GB)
telemt_user_octets_to_client{user="hello"} 97996461264 (91.27 GB)
telemt_user_connections_total{user="hello2"} 1
telemt_user_octets_from_client{user="hello2"} 140 (140 B)
telemt_user_octets_to_client{user="hello2"} 104 (104 B)
telemt_user_unique_ips_current{user="hello"} 62
```