# Server Metrics 2026-03-05 00:27:34 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.2.1

telemt_uptime_seconds 12848.4 (3h 34m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 105583
telemt_connections_bad_total 1410
telemt_handshake_timeouts_total 766
telemt_upstream_connect_attempt_total 18054
telemt_upstream_connect_success_total 17886
telemt_upstream_connect_fail_total 53
telemt_upstream_connect_attempts_per_request{bucket="1"} 17885
telemt_upstream_connect_attempts_per_request{bucket="2"} 54
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11453
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6337
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 35
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 61
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 53
telemt_me_keepalive_timeout_total 555
telemt_me_reconnect_attempts_total 8540
telemt_me_reconnect_success_total 8533
telemt_me_reader_eof_total 8847
telemt_me_idle_close_by_peer_total 8846
telemt_me_route_drop_no_conn_total 28358
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_single_endpoint_shadow_rotate_total 59
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 134
telemt_desync_full_logged_total 80
telemt_desync_suppressed_total 54
telemt_desync_frames_bucket_total{bucket="1_2"} 56
telemt_desync_frames_bucket_total{bucket="3_10"} 69
telemt_desync_frames_bucket_total{bucket="gt_10"} 9
telemt_me_writer_removed_unexpected_total 8906
telemt_me_writer_restored_same_endpoint_total 8513
telemt_me_writer_removed_unexpected_minus_restored_total 393
telemt_user_connections_total{user="hello"} 92090
telemt_user_connections_current{user="hello"} 292
telemt_user_octets_from_client{user="hello"} 2895833152 (2.70 GB)
telemt_user_octets_to_client{user="hello"} 49891459952 (46.47 GB)
telemt_user_unique_ips_current{user="hello"} 36
```

## server2

```
telemt 3.2.1

telemt_uptime_seconds 12843.2 (3h 34m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 41180
telemt_connections_bad_total 786
telemt_handshake_timeouts_total 1022
telemt_upstream_connect_attempt_total 13992
telemt_upstream_connect_success_total 13683
telemt_upstream_connect_fail_total 56
telemt_upstream_connect_attempts_per_request{bucket="1"} 13673
telemt_upstream_connect_attempts_per_request{bucket="2"} 66
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9036
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4543
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 104
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 56
telemt_me_keepalive_timeout_total 1024
telemt_me_reconnect_attempts_total 5333
telemt_me_reconnect_success_total 5307
telemt_me_reader_eof_total 5384
telemt_me_idle_close_by_peer_total 5383
telemt_me_route_drop_no_conn_total 12663
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_single_endpoint_outage_enter_total 1
telemt_me_single_endpoint_outage_exit_total 1
telemt_me_single_endpoint_outage_reconnect_attempt_total 3
telemt_me_single_endpoint_outage_reconnect_success_total 1
telemt_me_single_endpoint_quarantine_bypass_total 3
telemt_me_single_endpoint_shadow_rotate_total 58
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 138
telemt_desync_full_logged_total 53
telemt_desync_suppressed_total 85
telemt_desync_frames_bucket_total{bucket="1_2"} 40
telemt_desync_frames_bucket_total{bucket="3_10"} 50
telemt_desync_frames_bucket_total{bucket="gt_10"} 48
telemt_pool_swap_total 1
telemt_pool_force_close_total 34
telemt_me_writer_removed_unexpected_total 5488
telemt_me_writer_restored_same_endpoint_total 5282
telemt_me_writer_removed_unexpected_minus_restored_total 206
telemt_user_connections_total{user="hello"} 37151
telemt_user_connections_current{user="hello"} 107
telemt_user_octets_from_client{user="hello"} 332054048 (316.67 MB)
telemt_user_octets_to_client{user="hello"} 10296960612 (9.59 GB)
telemt_user_unique_ips_current{user="hello"} 25
```

## server3

```
telemt 3.2.1

telemt_uptime_seconds 12839.8 (3h 33m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 95490
telemt_connections_bad_total 1311
telemt_handshake_timeouts_total 698
telemt_upstream_connect_attempt_total 5672
telemt_upstream_connect_success_total 5616
telemt_upstream_connect_fail_total 20
telemt_upstream_connect_attempts_per_request{bucket="1"} 5616
telemt_upstream_connect_attempts_per_request{bucket="2"} 20
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2920
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2670
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 26
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 20
telemt_me_keepalive_timeout_total 56
telemt_me_reconnect_attempts_total 281
telemt_me_reconnect_success_total 291
telemt_me_reader_eof_total 280
telemt_me_idle_close_by_peer_total 280
telemt_me_route_drop_no_conn_total 27126
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_shadow_rotate_total 55
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 172
telemt_desync_full_logged_total 52
telemt_desync_suppressed_total 120
telemt_desync_frames_bucket_total{bucket="1_2"} 43
telemt_desync_frames_bucket_total{bucket="3_10"} 58
telemt_desync_frames_bucket_total{bucket="gt_10"} 71
telemt_pool_swap_total 4
telemt_pool_force_close_total 98
telemt_me_writer_removed_unexpected_total 280
telemt_me_writer_restored_same_endpoint_total 271
telemt_me_writer_removed_unexpected_minus_restored_total 9
telemt_user_connections_total{user="hello"} 87708
telemt_user_connections_current{user="hello"} 175
telemt_user_octets_from_client{user="hello"} 1051618596 (1002.90 MB)
telemt_user_octets_to_client{user="hello"} 31282956212 (29.13 GB)
telemt_user_unique_ips_current{user="hello"} 20
```

## server4

```
telemt 3.2.1

telemt_uptime_seconds 44888.1 (12h 28m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 552644
telemt_connections_bad_total 80742
telemt_handshake_timeouts_total 14741
telemt_upstream_connect_attempt_total 20893
telemt_upstream_connect_success_total 20891
telemt_upstream_connect_attempts_per_request{bucket="1"} 20891
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12069
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8818
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_me_keepalive_timeout_total 257
telemt_me_reconnect_attempts_total 3042
telemt_me_reconnect_success_total 3023
telemt_me_reader_eof_total 3083
telemt_me_idle_close_by_peer_total 3083
telemt_me_route_drop_no_conn_total 186142
telemt_me_route_drop_channel_closed_total 1
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_single_endpoint_shadow_rotate_total 182
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 724
telemt_desync_full_logged_total 304
telemt_desync_suppressed_total 420
telemt_desync_frames_bucket_total{bucket="1_2"} 225
telemt_desync_frames_bucket_total{bucket="3_10"} 207
telemt_desync_frames_bucket_total{bucket="gt_10"} 292
telemt_pool_swap_total 17
telemt_pool_force_close_total 484
telemt_pool_stale_pick_total 22
telemt_me_writer_removed_unexpected_total 3084
telemt_me_writer_restored_same_endpoint_total 2996
telemt_me_writer_removed_unexpected_minus_restored_total 88
telemt_user_connections_total{user="hello"} 428652
telemt_user_connections_current{user="hello"} 105
telemt_user_octets_from_client{user="hello"} 5851051904 (5.45 GB)
telemt_user_octets_to_client{user="hello"} 159820382156 (148.84 GB)
telemt_user_unique_ips_current{user="hello"} 20
```

## server5

```
telemt 3.2.1

telemt_uptime_seconds 45247.3 (12h 34m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 537599
telemt_connections_bad_total 3857
telemt_handshake_timeouts_total 5912
telemt_upstream_connect_attempt_total 29144
telemt_upstream_connect_success_total 28987
telemt_upstream_connect_fail_total 62
telemt_upstream_connect_attempts_per_request{bucket="1"} 28987
telemt_upstream_connect_attempts_per_request{bucket="2"} 62
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 16842
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12035
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 110
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 62
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 437
telemt_me_reconnect_attempts_total 6537
telemt_me_reconnect_success_total 6516
telemt_me_reader_eof_total 6760
telemt_me_idle_close_by_peer_total 6759
telemt_me_route_drop_no_conn_total 236520
telemt_me_route_drop_channel_closed_total 2
telemt_me_hardswap_pending_ttl_expired_total 9
telemt_me_single_endpoint_shadow_rotate_total 184
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 831
telemt_desync_full_logged_total 302
telemt_desync_suppressed_total 529
telemt_desync_frames_bucket_total{bucket="1_2"} 170
telemt_desync_frames_bucket_total{bucket="3_10"} 351
telemt_desync_frames_bucket_total{bucket="gt_10"} 310
telemt_pool_swap_total 10
telemt_pool_force_close_total 420
telemt_pool_stale_pick_total 189
telemt_me_writer_removed_unexpected_total 6765
telemt_me_writer_restored_same_endpoint_total 6494
telemt_me_writer_removed_unexpected_minus_restored_total 271
telemt_user_connections_total{user="hello"} 487045
telemt_user_connections_current{user="hello"} 127
telemt_user_octets_from_client{user="hello"} 7382367420 (6.88 GB)
telemt_user_octets_to_client{user="hello"} 162759600720 (151.58 GB)
telemt_user_unique_ips_current{user="hello"} 26
```